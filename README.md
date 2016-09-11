# TTS bot for Discord.

## Usage

```
!tw 87 機器人 94 狂
```

```
!en hello world!
```

```
!kr 오빠
```

```
!jp かわいいです
```

## Docker

* Create discordapp bot, and get bot token
* Config `config/options.ini` by `config/example_options.ini`
* `docker run -it -v $(pwd)/config:/discord_tts_bot/config yongjhih/discord-tts-bot`

or

```sh
curl https://github.com/yongjhih/discord-tts-bot/raw/master/docker-compose.yml | docker-compose -f - up discord-tts-bot
```

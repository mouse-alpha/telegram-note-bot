# telegram-note-bot
Note Taking Bot for Telegram

# Installation
```shell
go mod tidy
```

# Run
```shell
go run .
```

# Docker
__Build__
```shell
docker build  -t telegram-bot:$(git rev-parse --short HEAD~0) .
```

__Run__
```shell
docker run -it --rm telegram-bot:$(git rev-parse --short HEAD~0)
```
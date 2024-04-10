# Dev configuration setup utility
Command: c4d-dev:setup

- Add the repository and the package to your project composer.json.

```{
    ...
    "require": {
        "ec-europa/test-command": "x.x.x"
    },
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/ec-europa/test-command"
        },
    ]
}```

- Check if the command is loaded.

$ docker-composer exec web ./vendor/bin/run 
Toolkit Runner 9.1.0

Usage:
  command [options] [arguments]
...
Available commands:
  c4d-dev
    c4d-dev:setup

node-powermate-launcher
=======================

An application laucher by Griffin PowerMate

## Installation

    $ npm install node-powermate-launcher

## Help

    $ npl --help

    Usage: app [options]

    Options:

      -h, --help                     output usage information
      -V, --version                  output the version number
      -d, --debug                    enables the debug mode
      -c, --config <path>            configuration file path to setup several servers

## Configuration

An example of config file:

```json
[
  {
    "label": "Bash commands"
  , "commands": [
      {
        "name": "List"
      , "exec": "ls -la"
      }
    , {
        "name": "Current folder"
      , "exec": "pwd"
      }
    ]
  }
, {
    "label": "Rymshots"
  , "commands": [
      {
        "name": "Rimshot"
      , "exec": "cvlc --novideo ./rimshot.mp3"
      }
    , {
        "name": "Money"
      , "icon": "./money_icon.png"
      , "exec": "cvlc --novideo ./cash-register-05.wav"
      }
    , {
        "name": "Money"
      , "icon": "./mario-coin.png"
      , "exec": "cvlc --novideo ./mario-coin.mp3"
      }
    ]
  }
]
```

## License

Check the `LICENSE` file




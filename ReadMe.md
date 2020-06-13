# Lazh-Logger

## Description

Utility to various application for logging.

## Installation

Just type the following statement to install library.

```node
npm install --save @lazh/logger
```

## Usage

```javascript
var logger = require("@lazh/logger");
```

It have 2 Modules are

1. LogLevel
2. Logger

### LogLevel :

#### Declaration : 
```javascript
    const log = new logger.Logger();
```

#### Options :

| Level | Name    | Color  |
| ----- | ------- | ------ |
| 0     | Off     | None   |
| 1     | Error   | Red    |
| 2     | Warning | Yellow |
| 3     | Info    | Blue   |
| 4     | Debug   | Gray   |


### Logger :

#### Declaration : 
```javascript
    const LogLevel = logger.LogLevel;
```

#### Options :

| Method               | Description                         | Default Level                   |
| -------------------- | ----------------------------------- | ------------------------------- |
| enableProductionMode | Enables production mode with Params | Warning - Can Change Via Params |
| enableTestMode       | Enables Testing mode with Params    | Debug - Can Change Via Params   |
| debug                | Logs with Debug with Message        | Debug                           |
| info                 | Logs with Info with Message         | Info                            |
| warn                 | Logs with Warning with Message      | Warning                         |
| error                | Logs with Error with Message        | Error                           |
| level                | Return Current Log Level            |                                 |
|                      |                                     |                                 |


## Credits

This Library is created based on Base Source of N


## License

This Package was created under the MIT license.

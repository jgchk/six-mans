<h1 align="center">
  <br>
    <img src="https://cdn.rawgit.com/jgchk/six-mans/blob/master/sixmans/resources/icon.svg" alt="Six Mans" width="200">
  <br>
    Six Mans
  <br>
</h1>

<h4 align="center">A Discord bot for Rocket League 6-Mans queues.</h4>
<br>


## Key Features

* Queue handling
* Vote for or auto-pick captains
* Pick or randomly assign teams

## Installation

1. Clone the repository (```git clone https://github.com/jgchk/six-mans.git```)
2. Install requirements (```pip install -r requirements.txt```)
3. Enter your bot's token in sixmans/config/config.ini (<a href="https://discordapp.com/developers/applications/me">Create bot here</a>)
4. Run sixmans/bot.py

## Usage

1. Add yourself to the queue with the ```queue``` command
2. Once at least 6 people are in the queue, use one of the following commands to start a game:
    * ```voting```: Vote for captains
    * ```captains```: Randomly choose captains
    * ```random```: Randomly assign teams

## Commands

The default command prefix is ">". This can be changed in the config.
```
QUEUING
    queue
        description: Add yourself to the queue
        aliases: q

    dequeue
        description: Remove yourself from the queue
        aliases: dq

    kick <player>
        description: Remove another player from the queue
        example: kick @jgchk

TEAMMAKING
    voting
        description: Start a game by voting for captains

    captains
        description: Start a game by randomly choosing captains

    random
        description: Start a game by randomly assigning teams
```

---


#### Contributors

Jake Cheek - [@jgchk](https://github.com/jgchk)

#### License

MIT
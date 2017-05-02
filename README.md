# TennisGame
Composer configuration and executable for quickly starting a PHPSpec based TDD code kata for the Tennis Game.

## Usage

[Install composer](https://getcomposer.org/download/)

$ `git clone  git@github.com:msojda/TennisGame.git`

$ `cd TennisGame`

$ `composer.phar install`

$ `bin/phpspec desc YourClass`

$ `bin/phpspec run`

Make sure that your game class implements `TennisGame`

## Plugging it in

Edit `bin/play` and replace `<your tennis game here>` with your game class name.

run `bin/play` to begin the game.

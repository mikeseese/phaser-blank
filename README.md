# phaser-blank
A simple blank PhaserJs project with a NodeJS webserver

## Install NodeJS

Head over to https://nodejs.org and download the latest "LTS" version (currently v12.18.4) by clicking on the green button that says "<version> LTS". Don't download the "Current" version; it's "bleeding edge" and may contain bugs.

## Install a Code Editor

You may have a code editor already. You can make PhaserJS games with just Notepad, but there are a lot of benefits of using an editor. I **highly recommend** with years of experience to go grab Visual Studio Code at https://code.visualstudio.com/. It works on Windows, Mac, and Linux, and it supports several languages with extensions. It's easy to use. It's what I use for my professional job every day. It will help out later on this tutorial, but I will provide other generic options too.

## Download this Project

If you haven't already, you can download this project by clicking [here](https://github.com/seesemichaelj/phaser-blank/archive/master.zip). Unzip/Extract that file and you should have the project ready to go. Once you've extracted it, you should see a `phaser-blank-master` folder. You might have a a `phaser-blank-master` folder in another `phaser-blank-master` folder. In this tutorial, we'll be talking about the inside folder (which contains this `README.md` file).

![image](https://user-images.githubusercontent.com/549323/94236587-54521f00-fec2-11ea-84d3-6b58eee26059.png)

## Open the Project in Your Editor

If you're using a code editor like Visual Studio Code, you can likely open the `phaser-blank-master` folder that you extracted in the last step. With Visual Studio Code, you can right click on the `phaser-blank-master` folder that you extracted and click **Open with Code**

![image](https://user-images.githubusercontent.com/549323/94236617-63d16800-fec2-11ea-8772-4d743e854cca.png)


## Open a Terminal

### Using VS Code

VS Code comes with a terminal in the window for easy access. Open it by clicking `Terminal > New Terminal` in the top menu bar

![image](https://user-images.githubusercontent.com/549323/94236309-dc83f480-fec1-11ea-88d6-ce7b09503390.png)

### Everything Else

If you're not using Visual Studio Code, you will need to open a terminal to run a command.

If you're on Windows, you can `Shift+Right Click` on that same `phaser-blank-master` folder and click **Open Powershell Here**

![image](https://user-images.githubusercontent.com/549323/94236402-02a99480-fec2-11ea-8460-612d5cc420ea.png)

## Install Project Dependencies

We have to install some programs. In your terminal, enter the command `npm install`.

![image](https://user-images.githubusercontent.com/549323/94236714-8c596200-fec2-11ea-8070-58c4880b9a35.png)

## Run the Webserver to Access Your Game

You have to run a webserver to access your game. This project comes with one!

In the same terminal, run the command `npm start`

![image](https://user-images.githubusercontent.com/549323/94236853-b6ab1f80-fec2-11ea-845a-559930fcfa5c.png)

## Access Your Game

The prior command will show some URLs that you can click:

![image](https://user-images.githubusercontent.com/549323/94236919-d8a4a200-fec2-11ea-89d6-43fb94ff3ead.png)

You may need to `Alt+Click` or `Ctrl+Click` to open them. You can also manually put this URL in your browser to access the game. You should see a PhaserJS image show up!

![image](https://user-images.githubusercontent.com/549323/94236255-c2e2ad00-fec1-11ea-90e8-227d6cd51f63.png)

## Editing Your Game

You can edit the `public/index.html` file to change/add code to the game!

![image](https://user-images.githubusercontent.com/549323/94237024-0c7fc780-fec3-11ea-861f-4eeb28d112e2.png)
![image](https://user-images.githubusercontent.com/549323/94237079-23beb500-fec3-11ea-8e94-b021a683e806.png)
![image](https://user-images.githubusercontent.com/549323/94237128-3507c180-fec3-11ea-8e0c-d7caca527884.png)

## Have fun!

If you have questions, Google is your friend! A query like "phaserjs how to place image on click" may help you figure out how to place a building when a player clicks somewhere.

It may be good to read the Making Your First Phaser Game: https://phaser.io/tutorials/making-your-first-phaser-3-game/part1 to understand the different parts of Phaser and how it works.

There are some official tutorials here: https://phaser.io/learn/official-tutorials

You can find the official API documentation here: https://photonstorm.github.io/phaser3-docs/index.html


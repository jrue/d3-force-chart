## D3 Force Chart

This is a simple template for making a force bubble chart in D3. 

![Screenshot](https://raw.githubusercontent.com/jrue/d3-force-chart/master/screenshot.png)

## Install instructions

To install, fork this repo, then clone a copy to your computer. (Note: You will need [Node.js](https://nodejs.org/en/) installed for this command to work.) Open a Terminal window in the directory from where you cloned your repository, and run the following command:

```
npm install
```

Next, install Grunt globally if you don't have it already.

```
sudo npm install -g grunt-cli
```

Then, run grunt to initiate the watch task.

```
grunt
```

Open the URL in your browser and modify the files in the `src` folder. 

## Deploy to Github Pages

To deploy to Github, simply run the deploy command, which will copy the `dist` folder to gh-pages branch.

```
grunt deploy
```


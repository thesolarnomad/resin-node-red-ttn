# Node RED (TTN-enabled) for resin.io

This is a simple skeleton node-red with TTN input enabled project that works on any of the [resin.io][resin-link] supported devices.

This project simply runs node-red on port `:80` of your resin.io device.

## Getting started
To get this project up and running, you will need to signup for a resin.io account [here][signup-page] and set up a device, have a look at our [Getting Started tutorial][gettingStarted-link]. Once you are set up with resin.io, you will need to clone this repo locally:
```
$ git clone git@github.com:thesolarnomad/resin-node-red-ttn.git
```
Then add your resin.io application's remote repository to your local repository:
```
$ git remote add resin username@git.resin.io:username/myapp.git
```
and push the code to the newly added remote:
```
$ git push resin master
```

[resin-link]:https://resin.io/
[signup-page]:https://dashboard.resin.io/signup
[gettingStarted-link]:http://docs.resin.io/#/pages/installing/gettingStarted.md

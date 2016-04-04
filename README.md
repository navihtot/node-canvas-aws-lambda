# node-canvas-aws-lambda

Node canvas module with compiled dependency libraries. Based on [node-canvas-aws-lambda-example](https://github.com/WebSeed/node-canvas-aws-lambda-example) - added some additional libs that were required (at least for me to get it working), nice [how to guide](https://github.com/navihtot/node-canvas-aws-lambda/blob/master/how-to.md) for compiling libraries on EC2 instance, and script `libs_build` that does libs downloading and compiling for you (simple script which could break if i.e. curl fails downloading...).
Also libraries are sparated in `/lib` folder.



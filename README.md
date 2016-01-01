# generator-alfresco [![Build Status](https://secure.travis-ci.org/binduwavell/generator-alfresco.png?branch=master)](https://travis-ci.org/binduwavell/generator-alfresco) [![Coverage Status](https://coveralls.io/repos/binduwavell/generator-alfresco/badge.svg?branch=master&service=github)](https://coveralls.io/github/binduwavell/generator-alfresco?branch=master) [![Join the chat at https://gitter.im/binduwavell/generator-alfresco](https://img.shields.io/badge/gitter-join%20chat%20%E2%86%92-brightgreen.svg)](https://gitter.im/binduwavell/generator-alfresco?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![create project on Codenvy](https://img.shields.io/badge/codenvy-clone-blue.svg)](https://codenvy.com/factory?id=zmv24wynr689af6f) 

## Getting Started

### What is [Alfresco](http://www.alfresco.com)?

Alfresco is an open-source content management application. This project provides some tools for 
setting up and working with Alfresco extension/enhancement projects. It wraps and extends the
Alfresco SDK and specifically the All in One maven archetype.

### What is [Yeoman](http://yeoman.io)?

Yeoman is a command line tool that helps you to automate coding tasks. Out of the box, Yeoman 
doesn't do very much. It relies on a library of thousands of 
[generators](http://yeoman.io/generators/) to actually perform the coding tasks for you.

Yeoman lives in the [npm](https://npmjs.org) package repository. Assuming you have a recent
version of [node.js](http://www.nodejs.org) installed, you can use the following command
to install Yeoman.

```bash
npm install -g yo
```

### Installing and using the generator

You have a couple of options for installing Alfresco generator for Yeoman. Your choice will 
depend on if you plan to extend the generator or if you simply want to use it.

We have not pushed a version of the Alfresco generator to npmjs.org yet, so if you don't 
plan to make changes to the generator itself, run:

```bash
npm install -g binduwavell/generator-alfresco
```

WARNING: you will likely need to update this occasionally as the project is under active 
development.

Checkout the next section for what to do instead of this, if you plan to work on the 
generator code.

<!--
```bash
npm install -g generator-alfresco
```
-->

Now, assuming you have all of the pre-requisites installed (including appropriate
versions of node, npm, yeoman, this generator, Java and Maven.) You can create an 
Alfresco extension project using this generator. First of all you should create a 
new folder for your project and change into the new folder. Then run the 
following command:

```bash
yo alfresco
```

This will ask you a number of questions and then generate a project based on your
answers.

We are currently in the process of finalising the code that is needed for brining
new: local, remote and source modules into projects created with the generator.
Once that is done we will add sub-generators for creating things like webscripts, repo
actions, behaviors, workflows, etc.


### Try The Project / Contribute

If you plan to to make changes to the generator itself, you'll want to
check it out (or fork it and checkout your own copy) from GitHub and 
then run the following command from the checked out project directory:

```bash
npm install
npm link # may need sudo
```

This is essentially the same as the ```npm install -g binduwavell/generator-alfresco```
command above, but you'll have a project directory where you can tweak things, and
push updates back to GitHub.

Pull requests are very welcome! Please make sure to add/update tests appropriately.

Click the following link to open a clone of this project in Codenvy (a cloud IDE): 
[![create project on Codenvy](https://img.shields.io/badge/codenvy-clone-blue.svg)](https://codenvy.com/factory?id=zmv24wynr689af6f). 

Clicking the button will create a temporary workspace at Codenvy with a clone of this project, 
allowing you to run the generator in an embedded docker container called a runner. 
You can make edits to the generator-alfresco project, test them and ultimately send pull requests.
You can even run the Alfresco All-In-One project produced by the generator in the runner.

WARNING: The workspace generated by this link is temporary, persist it if you want to save your 
work for later.

Here is a video showing the process:

[![watch video demo using Codenvy](http://img.youtube.com/vi/Pq5IwG5Aq0Q/0.jpg)](http://www.youtube.com/watch?v=Pq5IwG5Aq0Q)

## Getting Help

If you find a bug or something is confusing, you can review [existing](https://github.com/binduwavell/generator-alfresco/issues) or create a [new](https://github.com/binduwavell/generator-alfresco/issues/new) issue in this project. If you'd like to chat, you can reach out on our [Gitter](https://gitter.im/binduwavell/generator-alfresco) channel.

## License

Apache 2.0

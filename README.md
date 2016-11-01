# Project Name
TagMe

Photo and video journaling with automated tagging

## Team

  - __Product Owner__: Bobby Wei
  - __Scrum Master__: Bobby Wei
  - __Development Team Members__: Kyle Chun, Karina Kinaman, Bill Zito, Bobby Wei

## Table of Contents

1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Development](#development)
    1. [Installing Dependencies](#installing-dependencies)
    1. [Tasks](#tasks)
1. [Team](#team)
1. [Contributing](#contributing)

## Usage
 Works on iOs devices and simulator (not tested with android).

## Requirements

- Node 0.10.x
- React Native
- etc

## Development

### Installing Dependencies

After you install things, it should run smoothly :). 

From within the root directory:

```sh
npm install
brew update
brew install imagemagick
```
From inside the client folder:
```sh
npm install
```
1. Download Xcode https://itunes.apple.com/us/app/xcode/id497799835?mt=12

2. Download the Exponent Development Environment (XDE) [for Mac](https://xde-updates.exponentjs.com/download/mac) or [for Windows](https://xde-updates.exponentjs.com/download/win32)

3. Download watchman (https://docs.getexponent.com/versions/v10.0.0/introduction/installation.html at bottom)

4. Once XDE is installed, go to 'open project' and choose the client folder

5. [Add environment variables for Amazon S3](http://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html#cli-environment)

### Roadmap

View the project roadmap [here](https://github.com/hr-memories/greenfield/issues)

Issues to be aware of: 

1. Sometimes the caption will render as a tag. This is an async issue becuase we use the response time from the server to render it in client/memory.js

2. not encrypting passwords

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines.

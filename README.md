# Graph Explorer

Open source, extendable data visualiser for Apache TinkerPop's Gremlin supported graph databases.

[![Apache license](https://img.shields.io/badge/license-Apache-blue.svg)](https://github.com/invanalabs/graph-explorer/blob/master/LICENSE) 
[![Build Status](https://travis-ci.org/invanalabs/graph-explorer.svg?branch=master)](https://travis-ci.org/invanalabs/graph-explorer)
[![Latest Demo](https://img.shields.io/badge/try%20demo-latest%20version-blue)](https://graph-explorer-edge.herokuapp.com)
[![Stable Demo](https://img.shields.io/badge/try%20demo-stable%20version-blue)](https://graph-explorer.herokuapp.com)
[![Docker pulls](https://img.shields.io/docker/pulls/invanalabs/graph-explorer)](https://hub.docker.com/r/invanalabs/graph-explorer)
[![Commit Activity](https://img.shields.io/github/commit-activity/m/invanalabs/graph-explorer)](https://github.com/invanalabs/graph-explorer/commits)

**Note:** You still need gremlin server running on your local or remote.

**This project is at Alpha Release currently, and expected 
to go into Beta in few weeks depending on the feed back
from the Community.** You can access live version of the demo hosted on heroku.


## Install on Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/invanalabs/graph-explorer/tree/master)

Get the UI graph-explorer server live in minutes. 
 
 
 
## Install using Docker

#### Use Image from Docker Hub

```shell script.
# for latest release
docker run -p 8888:8888 -d --name graph-explorer invanalabs/graph-explorer

```

#### Build and Deploy from Code
```shell script
git clone git@github.com:invanalabs/graph-explorer.git
cd graph-explorer
docker build . -t invana-graph-explorer 
docker run -p 8888:8888 -d invana-graph-explorer
```

## Screenshots
![1](./docs/screenshots/1.png)
![2](./docs/screenshots/2.png)
![3](./docs/screenshots/3.png)
![4](./docs/screenshots/4.png)
![5](./docs/screenshots/5.png)
![6](./docs/screenshots/6.png)


## License

Apache License 2.0

## Support 

For any further queries or dedicated support, please feel free to get in touch with me at hi[at]invana.io.

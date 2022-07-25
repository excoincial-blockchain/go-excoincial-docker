# Local go-Excoincial node docker image
[![GitHub stars](https://img.shields.io/github/stars/excoincial-blockchain/go-excoincial-docker.svg?label=&#9733;%20Stars&maxAge=2592000)](https://GitHub.com/excoincial-blockchain/go-excoincial-docker/stargazers)
[![Made in Nigeria](https://img.shields.io/badge/made%20in-nigeria-008751.svg?labelColor=ddd&style=flat-square)](https://github.com/acekyd/made-in-nigeria)
[![Made in Ukraine](https://img.shields.io/badge/made_in-ukraine-ffd700.svg?labelColor=0057b7)](https://github.com/chernivtsijs/made-in-ukraine)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![GitHub license](https://badgen.net/github/license/excoincial-blockchain/go-excoincial-docker)](https://github.com/excoincial-blockchain/go-excoincial-docker/blob/master/LICENSE)

[![GitHub watchers](https://img.shields.io/github/watchers/excoincial-blockchain/go-excoincial-docker.svg?style=social&label=Watch&maxAge=2592000)](https://GitHub.com/excoincial-blockchain/go-excoincial-docker/watchers/)

A script to build docker image for running local node

## Usage with docker-compose

Requirements:
- Docker installed locally.
- Docker-compose installed locally.

Clone the repository locally.

Run
<pre>
docker-compose up -d
</pre>

The network should start and synchronize without any further configuration.
The network implements the Clique protocol (Proof-of-Authority), thus the network runs efficiently and does not consume much of computational power.

Run
<pre>
docker-compose logs -f
</pre>
and once finished monitoring press ctrl-c

## Usage without docker-compose

Requirements:
- Docker installed locally.

Run
<pre>
docker pull excoincial/gexl:latest
</pre>

<pre>
docker run excoincial/gexl:latest
</pre>

The network should start and synchronize without any further configuration.
The network implements the Clique protocol (Proof-of-Authority), thus the network runs efficiently and does not consume much of computational power.

## After test-running Docker image

Make sure that node is operational and refer to Docker tutorials to plan further steps.

## Contribution

Thank you for considering to help out with the source code! We welcome contributions
from anyone on the internet, and are grateful for even the smallest of fixes!

If you'd like to contribute to go-excoincial-docker, please fork, fix, commit and send a pull request
for the maintainers to review and merge into the main code base.

## License

This repository is licensed under the MIT and references products of go-excoincial libraries and binaries licensed under the
[GNU Lesser General Public License v3.0](https://www.gnu.org/licenses/lgpl-3.0.en.html) referenced within the section that follows.
MIT License does not apply to go-excoincial libraries and binaries.

MIT License

Copyright (c) 2022 Excoincial

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## License reference

The go-excoincial library (i.e. all code outside of the `cmd` directory) is licensed under the
[GNU Lesser General Public License v3.0](https://www.gnu.org/licenses/lgpl-3.0.en.html),
also included in our repository in the `COPYING.LESSER` file.

The go-excoincial binaries (i.e. all code inside of the `cmd` directory) is licensed under the
[GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html), also
included in our [repository](https://github.com/excoincial-blockchain/go-excoincial) in the `COPYING` file.

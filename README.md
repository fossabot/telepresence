# [Documentation](https://telepresence.io) - start here!

[![Build Status](https://travis-ci.org/datawire/telepresence.svg?branch=master)](https://travis-ci.org/datawire/telepresence)
[![Join the chat at https://gitter.im/datawire/telepresence](https://badges.gitter.im/datawire/telepresence.svg)](https://gitter.im/datawire/telepresence?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fazatoth%2Ftelepresence.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fazatoth%2Ftelepresence?ref=badge_shield)

## Demo

[![asciicast](https://asciinema.org/a/117761.png)](https://asciinema.org/a/117761)

## Telepresence: fast, realistic local development for Kubernetes microservices

Have you ever wanted the quick development cycle of local code while still having your code run within a remote Kubernetes cluster?
Telepresence allows you to run your code locally while still:

1. Giving your code access to Services in a remote Kubernetes cluster.
2. Giving your code access to cloud resources like AWS RDS or Google PubSub.
3. Allowing Kubernetes to access your code as if it were in a normal pod within the cluster.

## Quick Start

1. [Install locally](https://www.telepresence.io/reference/install) with Homebrew, apt, or dnf.

2. Run `telepresence`.

3. You now have a shell that proxies connections to Kubernetes.

For more about Telepresence, and the various options, [read the documentation](https://www.telepresence.io/discussion/overview).

## About Telepresence

Telepresence is an open source project by [Datawire](https://www.datawire.io), and licensed under the Apache 2.0 License.


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fazatoth%2Ftelepresence.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fazatoth%2Ftelepresence?ref=badge_large)
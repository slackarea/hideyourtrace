# hideyourtrace
Connect your environment to multiple tor nodes via socks5

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Linux system Debian/Ubuntu based
```

### Installing

A step by step series of examples that tell you how to get a development env running

```
apt-get install -y bind9
apt-get install -y tor haproxy redsocks
```

A copy of cloudflared or another DoH


```
wget https://bin.equinox.io/c/VdrWdbjqyF/cloudflared-stable-linux-amd64.deb
dpkg -i cloudflared-stable-linux-amd64.deb

Prevent modification to /etc/resolv.conf

```
chattr +i /etc/resolv.conf
```

Copy each configuration files in the right path

...

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/slackarea) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

cooming soon

## Authors

* **Vincenzo Ingrosso** - *Initial work* - [slackarea](https://github.com/slackarea)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc

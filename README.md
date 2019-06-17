## tellnet

Check multiple IP addresses connectivity.

## Installation

Clone this repository and make symlink:

```
$ git clone https://github.com/nasrulhazim/tellnet.git
$ cd tellnet
$ ln -s tellnet /usr/bin/tellnet
```

## Usage

```
$ tellnet 10.10.0.01:80,443,22 10.20.0.01:80,443,22 10.30.0.01:22,3306 10.40.0.01:22,6379
```

## License

This package is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).

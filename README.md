## Sensu-Plugins-syslog-ng

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-syslog-ng.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-syslog-ng)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-syslog-ng.svg)](http://badge.fury.io/rb/sensu-plugins-syslog-ng)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-syslog-ng/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-syslog-ng)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-syslog-ng/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-syslog-ng)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-syslog-ng.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-syslog-ng)

## Functionality

## Files
 * bin/metrics-syslog-ng

## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-syslog-ng -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-syslog-ng`

#### Bundler

Add *sensu-plugins-disk-checks* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-syslog-ng' do
  options('--prerelease')
  version '0.0.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-syslog-ng' do
  options('--prerelease')
  version '0.0.1'
end
```

## Notes

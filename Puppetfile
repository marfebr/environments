#!/usr/bin/env ruby
#^syntax detection

forge "https://forgeapi.puppetlabs.com";

mod 'marfebr-confsbase'
mod 'marfebr-memcached'
mod 'marfebr-mysqlserver'

mod 'puppet-webserver',
  :git => 'https://github.com/marfebr/puppet-webserver.git',
  :branch => 'production'

mod 'puppet-balancer',
  :git => 'https://github.com/marfebr/puppet-balancer.git',
  :branch => 'production'

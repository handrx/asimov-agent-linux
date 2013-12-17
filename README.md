asimov-agent-linux
==================

Linux deploy agent for asimov

Todo List:
==================

Design language - perl

modules used: 
- HTTP::Server::Simple::CGI
- HTTP::Server::Simple::Static
- LWP
- JSON::Parse
- Digest::MD5
- Sys::Hostname

create perl modules:
- http server
- apiKey generator
- json generator based on the config file
- heartbeat module
- config files parser
- config files definition
- units/list module
- versions module
- deploy module
- deploy log module
- log module
- service configuration module 
- module to push/pull code revision

system modules:
- agent init script as a service (/etc/init.d)
- install script

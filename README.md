## README:

This is a simple wrapper around a config file in order to use a conf.d structure. It allows you
to use a conf.d/ directory insted of a single config file. It is easy to setup, but it will
force you to use ONLY a conf.d directory and stop using the single config file.

It is completed developed in bash and it should work in any UNIX enviroment.

In order to use it, you will need to provide this 3 variables:

* CONFDW_CONF - this is the path to the config file
* CONFDW_DIR  - this is the path to the directory that you want to use as conf.d
* CONFDW_APP  - this is the path to the app that you want to run


### EXAMPLE:

$ CONFDW_CONF='~/user/.ssh/conf' CONFDW='~/user/.ssh/conf.d' CONFD_APP='ssh' ./confdw

See the wrappers directory for more examples.

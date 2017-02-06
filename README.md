This is a Docker container for running both [Squid](https://github.com/sameersbn/docker-squid) and the [Saboteur](https://github.com/tomakehurst/saboteur) network fault tolerance tool.

Both services expose their usual ports, so 3128 for Squid and 6660 for Saboteur.

This is intended for use in doing network fault tolerance during test automation.  Setup your system to use localhost:3128 as a proxy then poke Saboteur as normal.

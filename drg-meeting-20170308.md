DRG Deep Reform Group

## Part 1: key server

devOps: key server, https certificate, (secret key)

standalone server

mailvelope server

deliverable: key server +/ api , smtp, 

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

## Part 2: architecture

nas, client -> (part2) ->....

three options:

1. standalone server, multiple nas waterwheel
2. standalone server, nginx external dns/built-in dns reverse-proxy, + multiple docker / waterwheel
3. standalone server, nginx reverse-proxy + docker cluster (LAN) + redis / database

OPEN Problem:

1. user-nas binding, one user own nas, other uses hosted by nas. <- it is a binding.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Travis CI => 1) installer binary package 2) // hot-update package

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

check list:
1. Travis CI, electron builder, macOS software sign (require certificate), publish to github (require rsa key)
2. AppVeyor, electron builder, publish to github (require rsa key)






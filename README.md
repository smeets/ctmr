ctmr - a cookie based timer experiment
=====================================

A short 2-hour project for experimenting with cookies
and their expiration times.

Starting philosophy was that if cookies expired by themselves then 
they could be viewed as a (self cleaning) timer. After some investigation
I found out that expiration dates aren't accessiable from
client-side, so now everything is baked into the cookie value instead...

Local storage is looking good  ._.

how-to
------

1. install node js
2. pull and run `node server.js`
3. browse to localhost:8080
4. enjoy all your timing needs
5. terminate timer by clicking on it

notes on input
--------------
The timer parser currently accepts the following:

13h:4m:22s -- offset into the future, accepts any combination

13:04:22 -- specific time today, or tomorrow if time has passed

license
-------
MIT
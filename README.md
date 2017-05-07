Description:
============

`easy-countdown` is a simple yet flexible countdown timer for the Linux command
line.

Usage:
======

**Countdown with a time duration:**

`$> easy-countdown 10m "Meeting starts now"`

The time duration is expressed in simple `h, m, s` notation.
Some examples: `10s`, `15m`, `5m30s`, `3h`, `4h45m`, `6h25m45s`.

**Countdown with a discrete time value:**

`$> easy-countdown 17:30 "Time to leave"`

The discrete time value is expressed in `HH:MM[:SS]` notation.
Some examples: `10:30`, `12:45:26`.

If the time value has already passed on the current day, then it is assumed that
the user wants to countdown until the given time on the next day.

Supported distributions:
========================

`easy-countdown` has been confirmed to work on Ubuntu 16.10.

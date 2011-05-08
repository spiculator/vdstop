vdstop
======

## ABOUT

`vdstop` is an interactive tool to monitor per-VDS activity
(cpu, memory usage, IO) for OpenVZ,
written by Sergey Redin sergey@redin.info for [1Gb.ru](http://www.1gb.ru/).

## REQUIREMENTS

* Linux
* OpenVZ
* perl with `Term::ReadKey`, `Number::Bytes::Human` and `Term::ANSIColor` modules.

## INSTALLATION

Copy `vdstop` somewhere to your `PATH` (e.g. to `/usr/local/bin`).

## USAGE

Run `vdstop -h` for command line help.
Run `vdstop` and hit `h` for help on interactive commands.

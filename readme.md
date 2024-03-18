```shb
$ sbt '+ compile'
$ srcclr scan --debug | grep 'Building graph' | sed -n 's/.*\(Building graph.*\)/\1/p'g
Building graph using Scala 2.10.6, sbt 0.13.16f
```.

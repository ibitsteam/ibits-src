Build instructions
===================

See readme-qt.rst for instructions on building iBITS QT, the
graphical user interface.

All of the commands should be executed in Terminal.app

```
sudo port install boost db48 openssl miniupnpc qrencode

cd ibits/src
make -f makefile.osx
```

```
./ibitsd --help  # for a list of command-line options.

./ibitsd -daemon # to start the ibits daemon.

./ibitsd help # When the daemon is running, to get a list of RPC commands
```

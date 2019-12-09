# learn_libevent
learn libeven, communicate between 2 computer by libevent. <br>

# Dependency
libevent: https://libevent.org/ <br>
libevent [version](https://github.com/libevent/libevent/releases/download/release-2.1.11-stable/libevent-2.1.11-stable.tar.gz)  <br>

    $ sudo apt-get install libssl-dev

    $ cd [PATH]/libevent-2.1.11-stable
    $ ./configure
    $ make
    $ make verify   # (optional)
    $ sudo make install

    Test
    $ cd sample
    // setup server.
    $ ./http-server 10.67.103.177 -p 6060 

    // client send file to server.
    $ ./https-client -url http://10.67.103.177:6060 -data ../tttt.txt

# Server

# Client

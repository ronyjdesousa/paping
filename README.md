**PAPING**

**Network Test Connection**

**Paping** is an open-source tool designed to **monitor the availability** of a 
TCP/IP network connection **TCP between two points**. It offers a 
straightforward approach to checking if a server is reachable and responsive
on a specific port. **Paping** enables real-time monitoring of server status,
aiding in the prompt detection of connectivity issues.

**BUILDING FROM SOURCE**

Paping requires the following elements to compile:

  * autoconf >= 2.71-3 <br>

Paping source installation is simple:

    $ ./autogen.sh
    $ ./configure
    $ make

Then as 'root':

    # make install

The autogen.sh can be used with the 'clean' option to remove all
generated files. Example:

    $ ./autogen.sh clean
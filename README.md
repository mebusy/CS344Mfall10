# CS344Mfall10
CS344M: Autonomous Multiagent Systems -- Fall 2010

[Dr.pstone's teaching](https://www.cs.utexas.edu/~pstone/teaching.shtml)

[The RoboCup Simulator Team Repository](http://medialab.di.unipi.it/Project/Robocup/pub)

[cs344m website](https://www.cs.utexas.edu/~pstone/Courses/344Mfall10)

[assignment](https://www.cs.utexas.edu/~pstone/Courses/344Mfall10/assignments/index.html)

[cs344m Resource](https://www.cs.utexas.edu/~pstone/Courses/344Mfall10/resources/index.html)


## Week 0: Introduction

[Austin Villa robot soccer team](https://www.cs.utexas.edu/users/AustinVilla)

### Computer Chess Vs. RoboCup

CHESS   | RoboCup
--- | ---
Static   |  Dynamic
Turn-taking | Real-time
Complete information | Incomplete info
Symbolic | Non-symbolic
Central control | Distributed control

## Week 1: Autonomous agents

- Reading
    - [Soccer Server 2D Manual](https://rcsoccersim.github.io/manual/)
    - Textbook:
        - **First edition**: sections 1, 1.1 (pages 1-7), 2-2.6 (pages 15-36)
        - Or **Second edition**: sections 1, 1.1 (pages 1-8), 2-2.5 (pages 21-38)



---

## Rcss Tools

- rcssserver
    - [rcssserver repo](https://github.com/rcsoccersim/rcssserver)
    - [rcssserver-docker](https://github.com/orangefoil/rcssserver-docker)
    ```bash
    docker run -d --name rcssserver -p 6000:6000 orangefoil/rcssserver
    ```
- rcsslogplayer
    - [Deprecated] The RoboCup Soccer Simulator Monitor v16 or later support the feature of game replay. Use rcssmonitor instead of rcsslogplayer.
- rcssmonitor
    ```bash
    PATH="/usr/local/opt/qt/bin:$PATH" PKG_CONFIG_PATH="/usr/local/opt/qt/lib/pkgconfig" ./configure
    ```





# simple-osc

This is practice of [logue-sdk](https://github.com/korginc/logue-sdk).

**simple**
This OSC simply play 440Hz + Param1 tone.

**basic**
This OSC simply play tone.


---

[logue-sdk](https://github.com/korginc/logue-sdk)を使ったサンプルです。

**simple**
440Hz + Param1 の音を鳴らすだけのOSCです。
どの鍵盤を押してもこの音しかなりません。実用的なものではなくライブラリのテストです。

**basic**
鍵盤の音を鳴らすだけのOSCです。
波形はwavesB[params1]を使います。

## How to build?

Use https://github.com/inajob/logue-sdk-docker

**linux and macOS**

```
$ git clone https://github.com/inajob/logue-sdk-docker
$ docker run -v `pwd`:/work/logue-sdk/platform/nutekt-digital/demos inajob1/logue-sdk-docker sh -c "cd logue-sdk/platform/nutekt-digital/demos/simple && make"
```

**Windows + Command Prompt**

```
> git clone https://github.com/inajob/logue-sdk-docker
> docker run -v :/work/logue-sdk/platform/nutekt-digital/demos inajob1/logue-sdk-docker sh -c "cd logue-sdk/platform/nutekt-digital/demos/simple && make"
```

**Windows + Git Bash**

```
$ git clone https://github.com/inajob/logue-sdk-docker
$ docker run -v /`pwd`:/work/logue-sdk/platform/nutekt-digital/demos inajob1/logue-sdk-docker sh -c "cd logue-sdk/platform/nutekt-digital/demos/simple && make"
```

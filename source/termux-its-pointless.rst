================================
Termux Its Pointless 源使用帮助
================================

地址
====

https://mirrors.ustc.edu.cn/termux-its-pointless

说明
====

Termux 第三方软件源，包含 gcc、R 语言和许多游戏

使用说明
========

添加 apt 存储库::

  wget -qO- https://its-pointless.github.io/setup-pointless-repo.sh | bash setup-pointless-repo.sh

使用 USTC 镜像::

  echo "deb https://mirrors.ustc.edu.cn/termux-its-pointless/24 termux extras" > $PREFIX/etc/apt/sources.list.d/pointless.list

相关链接
========

:GitHub: https://github.com/its-pointless/gcc_termux


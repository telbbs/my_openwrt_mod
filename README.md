my_openwrt_mod
==============

Install
-------

Add this line to your feeds.conf.default.

    src-git ramod git://github.com/telbbs/my_openwrt_mod.git 

And run

    ./scripts/feeds update -a && ./scripts/feeds install -a

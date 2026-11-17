# AIR6 routing feed

The `air6` branch starts from `ea8633da9c461a9bdc62a0323439d31180762e03`, the routing feed revision recorded for the previous AIR6 build. No routing package source changes were needed for the initial source migration.

This branch is the maintained source selected by `src-git routing https://github.com/royzheng/openwrt-routing.git;air6`. Record the actual commit in each build's `feeds.buildinfo`; the branch can advance independently of the parent workspace's submodule pointer.

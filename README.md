# Rpmfusion
```sh
rpm-ostree install \
  https://mirrors.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm \
  https://mirrors.rpmfusion.org/nonfree/fedora/rpmfusion-nonfree-release-$(rpm -E %fedora).noarch.rpm \
  ;
```

# Smplayer
```sh
rpm-ostree install \
  akmod-nvidia \
  smplayer \
  xorg-x11-drv-nvidia-cuda \
  ;
```

# PDP-7 with SIMH
Inspired by SimHでPDP-7ベアメタルプログラミング (http://yuma.ohgami.jp/)

## open-simh installation
```
# ref. SIMH-V4-status.md
sudo apt install libpcap-dev libpcre3-dev vde2 libsdl2-dev libsdl2-ttf-dev libedit-dev
    git clone https://github.com/open-simh/simh ~/git/simh &&
    cd ~/git/simh &&
    make pdp7 -j"$(nproc)" &&
    chmod +x BIN/pdp7 &&
    cp BIN/pdp7 ~/bin
```


# ohs2018-badge-firmware
```
ln -s $HOME/ohs2018-badge-firmware/badge/ $HOME/ohs2018-badge-firmware/micropython/ports/esp32/
git submodule update --init --recursive

cd micropython/
make -C mpy-cross
cd ports/esp32/
make

make erase
make deploy
```

# Calculator

CutefishOS Calculator

## Ubuntu Dependencies

```shell
sudo apt-get install cmake gcc qtbase5-dev qtdeclarative5-dev qml-module-qtquick2 qml-module-qtquick-controls2
```

## Build

```shell
mkdir build
cd build
cmake ..
make
```

## Install
```
sudo make install
```

## Uninstall

```shell
rm /usr/bin/cutefish-calculator
rm /usr/share/applications/cutefish-calculator.desktop
rm /usr/share/cutefish-calculator/translations/en_US.qm
rm /usr/share/cutefish-calculator/translations/fr_FR.qm
rm /usr/share/cutefish-calculator/translations/zh_CN.qm
```

## License

This project has been licensed by GPLv3.

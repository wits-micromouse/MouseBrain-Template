# Mouse Brain Template

## How to Build

### Build

```bash
git submodule update --init --recursive
mkdir bin
cmake -DCMAKE_EXPORT_COMPILE_COMMANDS=1 -S . -B ./bin/

```

### Run

```bash
cd bin
make
./wmm_mouse_template
```

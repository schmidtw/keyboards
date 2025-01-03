# keyboards
My keyboard firmware.

## Instructions:

1. Follow the instructions on qmk.fm.
2. Drop the files in to the qmk_firmware directory using the provided structure.
3. Compile using the CLI from qmk.fm or something like this:
```bash
qmk compile -kb keychron/q6/ansi -km schmidtw
```
4. Flash using the CLI from qmk.fm or something like this:
```bash
qmk flash -kb keychron/q6/ansi -km schmidtw
```
5. Put the Q6 keyboard into programming mode by pressing `ESC` and unplug/plug from USB.

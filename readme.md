I thinkk this builds??
```
west build --build-dir ./build/smcboard --pristine -b "seeeduino_xiao_ble" -s "$HOME/Development/zmk/app" -- -DZMK_CONFIG="$HOME/Development/zmk-smcboard/config" -DSHIELD="smcboard" -DZMK_EXTRA_MODULES="$HOME/Development/zmk-smcboard"
```

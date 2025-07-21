# Izmir ZMK Config 

## Building the Firmware with GitHub Actions

1. Fork the repository https://github.com/ozkan/izmir-zmk
2. Make changes to the [izmir.keymap](config/izmir.keymap) file in your repository.  
3. Commit changes to your repository
4. Go to `Actions`tab in your repository
5. Wait for the GitHub Action to complete
6. Grab `firmware.zip` file (it contains firmware)

## Flash firmware

1. Obtain `firmware.zip`
2. Unzip `firmware.zip`, you should have `izmir-nice_nano_v2-zmk.uf2` files
3. Connect selected halve to the PC via USB-C cable
4. Press `RESET` button **twice** to enter DFU mode. You should see new USB device in your file manager
5. Copy the corresponding firmware to the root directory of the new USB device

 Your device is now ready to use. Enjoy your enhanced experience! :tada:

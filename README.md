# rofi\_chromium\_profiles
Use rofi to directly open profiles in chromium-based browsers,
instead of using chromium's built-in profile switcher

## Sample Usage

```bash
rofi -show CHROMIUM:./rofi_chromium_profiles.sh 
```

## Dependencies
1 .`jq` is needed to parse chromium's "Local State" json file.

## Browser support
The script is currently configured for chromium,
but should theoretically work with *any* chromium-based browser.
Edit the variables `CHROMIUM_COMMAND` and `LOCAL_STATE_FILE` at the start
of the script to reflect your setup.

## Contributing
The script currently includes an example for using it with
flatpak'd Brave instead of native Chromium.
You are welcome to contribute configurations for other
browser/package manager combinations in the form of comment lines in
the script.
If you don't feel like opening a pull request,
you can also just open an issue and tell me what to add.


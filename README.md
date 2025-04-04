# template for developing rust on a m5stamps3 (or any other esp32s3 based board)
 IMPORTANT STEPS TAKEN FOR THIS TO WORK
 1. nix-ld must be enabled
 2. run espup
 3. copy the script it generates in ~ to shellhook
 4. you will need to make a symlink from a working version of rust analyser to the esp tool chain for it to work right, see https://www.reddit.com/r/rust/comments/13d2tls/rustanalyzer_and_toolchain_for_esp/

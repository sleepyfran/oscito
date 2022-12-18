# oscito

A tiny Operative System made in Rust following the [The Little Book About OS Development](http://littleosbook.github.io). OScito because -cito is the suffix for small things in Spanish :smiley:.

# How to run

I've only ran this on macOS, so not sure how it'd be for other systems. In macOS, you need to run the following commands to install the dependencies (assuming you're using Brew):

```bash
brew install cdrtools # Needed to generate ISO files.
brew install nasm # Needed to compile ASM code.
brew install i686-elf-binutils # Needed to run the appropiate linker later on.
brew install qemu # Needed to run the ISO somewhere :^)
```

Afterwards you'd be able to just run `make run` and OScito should be running on your computer inside of QEMU!

# A word...

I'm not very well versed in Rust nor in OS development. This is all just an effort to both improve my understanding of low-level stuff (following the book I linked above) and my Rust skills. So please, don't take any of this code as either gospel or idiomatic Rust :smiley:


# oreilly-qc.github.io
Code samples for the book *Programming Quantum Computers*, from O'Reilly Media

# What's the difference from original code?

This fork adds some niceities to the original UI:

1. Erase output box button now shows up in modern browser.
1. Auto-erase option added. Check the box, and the previous output will be cleared upon running the code.
1. The outpt message prints a timestamp at the top. This makes it visually aparent that something happened. Plus - it tells you the time :-)
1. You can run the code by hitting `F5` on your keyboard. This only works when the cursor is in the code text editor. If your cursor is anywhere else, the key will assume its normal OS / browser intended binding.
1. Original `qc.print()` had no line breaks. You had to add `\n` to each print statement explicitly. Checkbox added to modify that behavior in output panel. You can also use `qc.println('text-without-newline')` if writing new code. Squee!


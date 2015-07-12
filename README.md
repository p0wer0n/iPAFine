# iPAFine
iOS IPA package refine and resign

1. Refine App Name based on file name.
2. Inject dylib into executable (so you can hook and modify the third party app at runtime).
3. Resign the app to ipa. Support application identity entitlements that required in 8.1.3.

Support 32/64 and Universal (FAT_MAGIC and FAT_CIGAM from [pebble](https://github.com/crazypebble/iPAFine/commit/14583fad7b773a393d9136eb3c8db4cacb544ee2)) binary

Test only

//Added by p0wer0n

iPAFine is the currently only working ipa resigner for >iOS 8.3. It is tested and working on iOS 9.0 beta 3. I added a cool icon to it, and added a precompiled binary in the releases section of this project. I do not take credit for this work.

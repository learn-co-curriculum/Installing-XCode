---
  tags: xcode, command-line-tools, config
  languages: 
---

Installing XCode with Command Line Tools (GCC)
================

## Via the App Store (easiest way)

Just open up the App Store and search for XCode. You'll see the program, click install, login with your apple ID. XCode will begin downloading and installing, it's big, so it might take a second.

Once XCode is done, run it for the first time, it is in your `Applications` directory.

After agreeing to some terms, you'll be at the XCode Welcome screen where it asks you to either start a project or open one.

From your menu bar (or via pressing command+, `⌘ + ,`) to open you preferences. Go to the Downloads tab and under components, download the Command Line Tools Package. After that installs, you can quit XCode.

Open your terminal and type `gcc`, you should see something like:

```
i686-apple-darwin11-llvm-gcc-4.2: no input files
```

You're all set!

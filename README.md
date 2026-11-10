# Contextclip

A macOS menu bar app that copies text from anywhere on your screen. Press a hotkey, drag a box over anything, and the text lands on your clipboard. Recognition runs on your Mac through Apple's Vision framework, so nothing gets uploaded.

https://github.com/user-attachments/assets/d3110b31-89f5-4bd9-b348-dd1590069b10

## Requirements

- macOS 13 or later
- Xcode 15 or later (tested with 27.2)
- Homebrew, which `make setup` uses to install XcodeGen

## Setup

```bash
make setup
```

## Run

```bash
make run
```

To build a release and copy it to `/Applications`:

```bash
make install
```

## Test

```bash
make test
```

## Deploy

**Where it runs:** On your own Mac, from `/Applications`.

**Needs:** Only the requirements above.

```bash
make install
```

## Permissions

macOS asks for Screen Recording on the first capture. Without it the captured image comes out blank. Keep the app in `/Applications` if you turn on launch at login.

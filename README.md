Mint Screenshot
================

Mint Screenshot was created as a fork of GNOME Screenshot 41.
The list of merged PRs is at the end of the document.

It is a small tool for taking screenshots of the entire
desktop; the currently focused window; or screen area.

The program has been enriched and adapted for Linux Mint.

Issues should be reported at https://github.com/kacperpaczos/mint-screenshot/issues (search for your issue first).

### Dependencies

- GLib 2.36
- GTK+ 3.12
- X11

Merged from GNOME Screenshot

- [x] desktop: Remove outdated Bugzilla entries
- [x] Add info to README to report issues
- [x] Hardware support information
- [x] Added configuration option for flash
- [x] Add "snipping" to keywords
- [x] Adds a "Save And New" button
- [x] Adjust to small screensize


TODO
- [ ] Switch to gtk4
- [ ] Implement features from gnome builtin screenshot tool, like select windows from workspace or workspaces
- [ ] Implement some features from peek,
- [ ] Simple tools to edit screenshot
- [ ] Checkbox for endless mode
- [ ] Series of photos
- [ ] Wayland
- [ ] Refresh screen and about
- [ ] Switch to c++20
- [ ] flash, sound and saving in recent files configureable 61
- [ ] 52 Redesign screenshot-interactive-dialog based on mockups
- [ ] WIP: Make interactive mode default
- [ ] 32 Fixed crashing on wayland while trying to take a window screenshot when there are no windows



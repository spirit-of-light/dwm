# Patches
- [x] Added cool autostart patch
- [x] Applied attachdirection patch and set to 4
- [x] Added pertag patch
- [x] Applied push-nomaster patch
- [x] Applied bulkill patch
- [ ] Applied colorbar patch
- [ ] Applied warp patch
- [x] Applied taglayouts patch
- [ ] Applied custom urgent border patch
- [ ] Applied gridmode patch
- [ ] Moved grid layout to main file
- [x] Applied centeredmaster patch and removed the centered floating master functionality
- [x] Applied bottomstack patch without horizontal stacking functionality

# Other
- [x] Modified config.mk to compile on FreeBSD
- [x] Changed modkey to super
- [x] Added rm config.h to Makefile to regenerate the config because patches are applied to config.def.h. Annoying to always have to delete config.h manually.
- [x] Changed font to 3270NerdFontMono and increased font size to 12
- [x] Added *.diff to .gitignore
- [x] Added dwmblocks to autostart
- [x] Added sound control, added MPD control, added screenshot command, added keybinds
- [x] Removed tag activity highlight
- [ ] Disabled the removal of borders touching the edge of the monitor
- [ ] Removed border sharing because it's impossible to implement it in all other layouts

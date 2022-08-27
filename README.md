## @scotthansonde/electronLand

Dave Winer's container for Electron apps that use nodeStorage for identity. 

I've disabled hardware acceleration to work around a bug in Electron 7.1.10.

### Original README

This is now a available as a <a href="https://www.npmjs.com/package/electronland">package</a> on NPM and as a GitHub <a href="https://github.com/scripting/electronland">repository</a>.

More docs forthcoming.

8/3/17 by DW

### Update 2/16/20 by DW

Export shell.buildTabs so we can change the title of a tab from above. 

### Update 1/31/20; by DW

Fixed <a href="https://www.electronjs.org/releases/stable?version=6&page=5#release-notes-for-600">breakage</a> in shellNewFileDialog, shellChooseFolderDialog, shellOpenFileDialog.

Fixed some hard-coded icons used with Font-Awesome. Upgrading to the new version caused breakage. 

### Update 12/27/17 by DW

Made public along with the <a href="https://github.com/scripting/Scripting-News/issues/55">release</a> of <a href="https://github.com/scripting/electricPork">electricPork</a> as open source. The goal is to port electronLand to platforms other than the Mac. 


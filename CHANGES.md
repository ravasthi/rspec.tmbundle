This file is intended to give a quick overview of important and potentially non-backward-compatible changes. Please refer to the git log for a full list of changes.

# August, 2014
 
 * “Run Examples in selected files/directories” now runs all examples in `spec/` if nothing is selected (hint: use <kbd>⌘⇧A</kbd> to quickly deselect all files and directories).
 * __Drop support for TextMate 1 and RSpec 1__. Please use the legacy version from the branch “rspec1-textmate1” if necessary.
 * Change shortcut for __“Alternate File”__ from <kbd>⌃⇧↓</kbd> to <kbd>⌃⌥⇧↓</kbd>. You can get back the old shortcut by opening the bundle editor (“Bundles → Edit Bundles”), navigating to “RSpec → Menu Actions → Alternate File” and setting “Key Equivalent” accordingly. See [#57](https://github.com/rspec/rspec-tmbundle/issues/57) for the reason of this change.
myST3config
===========

My SublimeText3 personal settings.

## 1. User Preferences

### "auto_complete_commit_on_tab": true
This tells sublime what key will accept completion within the autocomplete popup. So tab will still activate snippets. You can try settings tab_completion to false.

### "bold_folder_labels": true
For themes that support it, this makes the folder name in the sidebar appear with a bold font.

### "caret_extra_width": 1 / "caret_style": "phase"
Control the caret style, easier to spot.

### "close_windows_when_empty": false
Set to true to close windows as soon as the last file is closed, unless there's a folder open within the window. This is always enabled on OS X, changing it here won't modify the behaviour.

### "color_scheme": "Packages/User/SublimeLinter/Lyte-Dark (SL).tmTheme"
This only matters if using the Lyte theme and wanting the dark colour scheme.

### "copy_with_empty_selection": false
If true, the copy and cut commands will operate on the current line when the selection is empty, rather than doing nothing. False to copy only when you select something.

### "detect_indentation": true
When set true, this will attempt to detect from a loaded file whether the tab key should insert spaces or tabs.

### "detect_slow_plugins": false
A plugin may be making SublimeText unresponsive by taking too long in its on_load callback. The popup message can be disabled via this setting

### "dictionary": "Packages/Language - English/en_GB.dic"
You can set the default dictionary to use for spelling check in Sublime. This sets the dictionary to British English.

### "ensure_newline_at_eof_on_save": true
Makes sure you have a last empty line when you save a file. Helpful if you concatenate without minifying as it keeps the code readable.

### "fade_fold_buttons": false
Always shows a triangle in the gutter when code is both folded AND unfolded.

### "file_exclude_patterns" / "folder_exclude_patterns"
Set these to your own liking

### "font_face": "Hack"
"Hack is hand groomed and optically balanced to be your go-to code face": http://sourcefoundry.org/hack/

### "font_options": [...] / "font-size"
Options for better readability. Of course they depend on the font in use.

### "highlight_line": true / "highlight_modified_tabs": true
These options help you identify where you changes are made in a file (before you save).

### "ignored_packages"
Set these to your own liking

### "indent_guide_options": []
This will turn on highlighting of the active indentation guide as well as the stacked, or parent, indentation guides.

### 	"open_files_in_new_window": false
OSX-Only: open file from Finder in new tab. not new window

### "origami_auto_close_empty_panes" / "origami_auto_zoom_on_focus"
These are Origami-specific. Origami is a package that splits the window however you like.

### "overlay_scroll_bars": "enabled"
Visual enhancement. Only show the scrollbars when actually scrolling (and don't take UI space).

### "rulers"
Helps you set a vertical line where you want your inline documentation to break

### "scroll_past_end": true
Sublime keeps scrolling after it reaches the end of the document. To me, this fixes a bug where the selection of the code in the last lines was always too quirky.

### "soda_folder_icons": true
Soda-theme specific. Displays the folder icons. (May be redundant now that Sublime has its own icons enabled by default)

### "spell_check": true
Enables spell checking.

### "tab_completion": true
Sets the TAB key to always complete the code suggestion.

### "tab_size": 2
Sets the default value for indentation.

### "theme": "SoDaReloaded Dark.sublime-theme"
My theme of choice.

### "translate_tabs_to_spaces": false
False because I'd rather use tabs than spaces. It's all about how someone likes to work, but on a document with a couple hundred lines of code, you'd save Kb by using tabs instead of spaces...

### "tree_animation_enabled": true
Visual enhancement. Controls side bar animation when expanding or collapsing folders.

### "trim_trailing_white_space_on_save": true
Remove all the blank spaces left at the end of a line, for a cleaner code.

### "wide_caret": true
One more setting to control the caret style, easier to spot.

### "word_separators": "./\\()\"'-:,.;<>~!@#%^&*|+=[]{}`~?"
Controls what characters are used as separators. If you remove the dash from here, you'll be able to double click on this-text and select it at once. Leave as it is if you want to select each word separately.

### "word_wrap": true
With this setting the code wraps once it hits the edge of the window



## 2. Key Bindings

All keys combination are commented inline or self-explanatory.
Change these to anything that does not conflict with any installed package.

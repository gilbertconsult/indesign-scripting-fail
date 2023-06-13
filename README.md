# indesign-scripting-fail
Public documentation of items that aren't in the InDesign scripting DOM

## app.generalPreferences.objectsMoveWithPage
The documentation states that this setting only affects page objects when the page is moved via the UI. InDeed, this setting will select/deselect the option in the InDesign Control Panel, but it has no affect on page items if a page is moved via scripting. No known workarounds. Documented 2023-06-12, InDesign vs. 18.3

## Hyperlink Alt Text
As of 2023-06-12, InDesign vs. 18.3 (also earlier), the `Alt Text` field cannot be scripted:

<img width="565" alt="image" src="https://github.com/gilbertconsult/indesign-scripting-fail/assets/10133752/d596b430-4c17-470c-883c-b93719e9db13">

## Type > Find/Replace Font
As of 2023-06-13, InDesign vs. 18.3 (also earlier), this command cannot be scripted. Possible workarounds involve scripting Find/Change routines to look for a specific font, or other scripting methods. But none of these workarounds work precisely the same what the Type > Find/Replace Font works.

## Various Preferences

Preferences > User Interface Scaling

Preferences > Type > Enable In-Menu Font Previews

Preferences > Type > Number of Recent Fonts

Preferences > Type >  Enable Japanese font preview in "find more"

Preferences > Type > Sort recent fonts list alphabetically

Preferences > Type > Preview fonts on hover

Preferences > Dictionary > Duden Dictionary > Show Hyphenation Options

Preferences > File Handling > Default Relink Folder

Preferences > File Handling > Hide New Layers When Updating or Relinking

Preferences > Clipboard Handling > Show Auto Style

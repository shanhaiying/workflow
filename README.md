These are the scripts, codes, etc. that I use in my workflow. They are located in different repos. This is my attempt to collect them together. Most these stuff are sync with [mackup](https://github.com/lra/mackup).

### Alfred
* **[AvaxHomeSearch](https://github.com/emraher/alfred/blob/master/AvaxHomeSearch.alfredworkflow):**  Search [AvaxHome](avxhome.se).

* **[ConvertRmdJekyllblogposttovanillamd](https://github.com/emraher/alfred/blob/master/ConvertRmdJekyllblogposttovanillamd.alfredworkflow):** Converts .Rmd posts written in R to vanilla md files. Requires [make.R](https://github.com/emraher/alfred/blob/master/make.R) file. You should also fix the paths.

* **[NewJekyllblogposts](https://github.com/emraher/alfred/blob/master/NewJekyllblogposts.alfredworkflow):** Create post, article, or page. You should fix the paths.

* **[NewSlidify](https://github.com/emraher/alfred/blob/master/NewSlidify.alfredworkflow):** Creates Slidify. Requires Rstudio and [Slidify](https://github.com/emraher/alfred/tree/master/Slidify). You should also fix the paths.

* **[ReferenceImporter](https://github.com/emraher/alfred/blob/master/ReferenceImporter.alfredworkflow):** From [reference-importer](https://github.com/andrewning/alfred-workflows-scientific/tree/master/reference-importer).

* **[SearchAlternativeTo](https://github.com/emraher/alfred/blob/master/SearchAlternativeTo.alfredworkflow):** Search [alternativeTo](https://alternativeto.net/).

### Bibdesk
* **[bibfetch.pl.scpt](https://github.com/emraher/Scripts/blob/master/Bibdesk/bibfetch.pl.scpt):** This a version of [mankoff/BibDeskAppleScripts/bibfetch.pl.scpt](https://github.com/mankoff/BibDeskAppleScripts). It searches web for the pdf of the selected bibtex entry in Bibdesk. It requires [bibfetch.pl](https://github.com/emraher/Scripts/blob/master/PerlScripts/bibfetch.pl) which is from [dschoepe/bibfetch](https://github.com/dschoepe/bibfetch). You should also fix the paths.

* **[Toggle Journal Abbreviation](https://github.com/emraher/Scripts/blob/master/Bibdesk/Toggle%20Journal%20Abbreviation.scpt):** This is [Jeremy Van Cleve's](http://vancleve.theoretical.bio/software/) Applescript. It requires [abbreviateJournalTitles.pl](https://github.com/emraher/Scripts/blob/master/PerlScripts/abbreviateJournalTitles.pl) along with the [abbreviations.txt](https://github.com/emraher/journal_abbreviations/blob/master/abbreviations.txt). You should also fix the paths.

### DEVONthink
* **[Annotation template with specific issue tagging___Ctrl-Alt-2](https://github.com/emraher/Scripts/DT/Annotation%20template%20with%20specific%20issue%20tagging___Ctrl-Alt-2.scptd):** [From DEVONthink forums](http://forum.devontechnologies.com/download/file.php?id=2019.)

* **[AddKeywordsToPdfMetadata___Ctrl-Alt-9](https://github.com/emraher/Scripts/DT/AddKeywordsToPdfMetadata___Ctrl-Alt-9.scptd):** Adds DEVONthink keywords to pdf metadata. Requires [exiftool](http://www.sno.phy.queensu.ca/~phil/exiftool/) to be installed.

* **[AddPathToPdfMetadata___Ctrl-Alt-0](https://github.com/emraher/Scripts/DT/AddPathToPdfMetadata___Ctrl-Alt-0.scptd):** Adds DEVONthink path to pdf metadata. Requires [exiftool](http://www.sno.phy.queensu.ca/~phil/exiftool/) to be installed.

* **[database_change_error](https://github.com/emraher/Scripts/DT/database_change_error.scpt):** Useless error script.

* **[DT_Skim](https://github.com/emraher/Scripts/DT/DT_Skim.scpt):** Useless script.

* **[RefreshAllRSS___Ctrl-Alt-1](https://github.com/emraher/Scripts/DT/RefreshAllRSS___Ctrl-Alt-1.scptd):** Refresh all RSS feeds.

* **[Remove all tags from selection](https://github.com/emraher/Scripts/DT/Remove%20all%20tags%20from%20selection.scpt):** Derived from "Remove tags from selection".

### Keyboard Maestro
* **[Capitalize All](https://github.com/emraher/KMmacros/blob/master/Capitalize%20All.kmmacros):** Capitalizes Bibdesk entries. This macro requires multiple Applescripts from [Christiaan Hofman](http://www.physics.rutgers.edu/~hofman/applescript/) to be installed. You should also fix the paths.

* **[Change pdf Metadata](https://github.com/emraher/KMmacros/blob/master/Change%20pdf%20Metadata.kmmacros):** Changes the metadata of selected pdf in Bibdesk. It depends on [changemetadata.sh](https://github.com/emraher/KMmacros/blob/master/changemetadata.sh) which requires [exiftool](http://www.sno.phy.queensu.ca/~phil/exiftool/) to be installed. You should also fix the paths.

* **[SkimToDTPO](https://github.com/emraher/KMmacros/blob/master/SkimToDTPO.kmmacros):** See **Popclip** below.


* ~~~~**[ReadMarkdownandTakeNoteDTPO](https://github.com/emraher/KMmacros/blob/master/ReadMarkdownandTakeNoteDTPO.kmmacros):** For the selected md file in DEVONthink, creates a note in nvAlt and opens Marked for the note.~~~~

* ~~~~**[ReadMarkdownandTakeNotePathFinder](https://github.com/emraher/KMmacros/blob/master/ReadMarkdownandTakeNotePathFinder.kmmacros):** For the selected md file in PathFinder, opens Marked and nvAlt.~~~~

### Popclip
* **[libgen](https://github.com/emraher/popclipextensions/tree/master/libgen.popclipext):** Search selected text in [Library Genesis](http://gen.lib.rus.ec/) with default browser.

* **[scihub](https://github.com/emraher/popclipextensions/tree/master/scihub%20.popclipext):** Search selected text in [Sci-Hub](http://www.sci-hub.club/) with default browser.

* **[skimdtpo](https://github.com/emraher/popclipextensions/tree/master/skimdtpo.popclipext):** Send highlights from [Skim](http://skim-app.sourceforge.net/) to [DEVONthink Pro Office](http://www.devontechnologies.com/products/devonthink/devonthink-pro-office.html). This requires the [SkimToDTPO.kmmacros](https://github.com/emraher/KMmacros/blob/master/SkimToDTPO.kmmacros) macro to be installed. See "How to Use" in macro.

### Services
* **[gitinfo](https://github.com/emraher/Scripts/tree/master/Automator/gitinfo.workflow/Contents):** Creates git repo in a selected folder in PathFinder with [gitinfo2](https://www.ctan.org/pkg/gitinfo2?lang=en) hooks created. Uses files from [emraher/gitinfo](https://github.com/emraher/gitinfo). You should also fix the paths.

* **[gitinit](https://github.com/emraher/Scripts/tree/master/Automator/gitinit.workflow/Contents):** Creates git repo in a selected folder in PathFinder.

### Sublime Text
* **[LaTeX_article.sublime-snippet](https://github.com/emraher/Scripts/tree/master/ST/LaTeX_article.sublime-snippet):** LaTeX article snippet for ST.

# MD-Dashing Theme 1.0 

## General Overview
This is an original, custom theme designed to work with several current Markdown Editors and Viewers.

<!-- It is a dark theme intended to convey clear hierarchy and scannability, while being easy on the eyes over extended periods of time. -->

![](http://jpgls.com/md-dashing-theme/example-images/LightPaper.png)

### Fonts
---  
Ideally, this theme is intended to make use of Adobe's Open Source fonts, **Adobe Source Sans Pro** and **Adobe Source Code Pro**. You can check out the **GitHub** Projects ([code](https://github.com/adobe/source-code-pro) - [sans](https://github.com/adobe/source-sans-pro)) or download the OTF files directly from **SourceForge** ([code](http://sourceforge.net/projects/sourcecodepro.adobe/files/) - [sans](http://sourceforge.net/projects/sourcesans.adobe/files/)). The easiest way to install the fonts though, is using Typekit ([code](https://typekit.com/fonts/source-code-pro) - [sans](https://typekit.com/fonts/source-sans-pro)) - assuming you have an account either directly or through Creative Cloud.

Alternate fallbacks have been defined in the stylesheet, but, I really would encourage you to get the *Source* fonts.

### Applications
---  
This theme was originally created for **[LightPaper](http://clockworkengine.com/lightpaper-mac/)**.

![](http://jpgls.com/md-dashing-theme/example-images/LightPaper.png) 

Thanks to [@staudi](https://github.com/Staudi)'s [Clearness Dark+ Theme](https://github.com/Staudi/Clearness-Dark-Plus) and it's documentation, I discovered that it also works well with:  

#### [MOU](http://mouapp.com/)

![](http://jpgls.com/md-dashing-theme/example-images/Mou.png)

#### [Marked 2](http://marked2app.com/)

![](http://jpgls.com/md-dashing-theme/example-images/Marked2.png)

#### [QLMarkdown](https://github.com/toland/qlmarkdown)

![](http://jpgls.com/md-dashing-theme/example-images/qlmarkdown-quicklook.png)

Installing it as a theme for QLMarkdown will have an effect the Finder Previews of MarkDown Files as well.

![](http://jpgls.com/md-dashing-theme/example-images/qlmarkdown-finderPreview.png)

In theory, this theme should also play nicely with any other markdown apps that use CSS to style the preview, and TXT files for the theme of the editor. If you happen to try it in any, I'd love to know how it turns out.

#### Fun Fact
I'm also building out a version of this theme for [FoldingText](http://www.foldingtext.com/) which is available in this repo: [ft-dashing-theme](https://github.com/designerJordan/ft-dashing-theme)

I've been tinkering with these fonts and colors for quite a while, across most apps I use regularly that allow for much customization of their appearance. I hope to continue rounding them up, polishing things, and sharing them. Apps that are hopefully coming sometime sort of soon-ish include:

* OmniGraffle
* OmniOutliner
* OmniFocus
* Sublime Text 3/2
* iTerm 2
* Alfred
* Path Finder
* LibreOffice

If you would like to request support for any other apps, let me know and we can take a look. Contact info is at the bottom of this doc.

## Installation

* Clone or [download](https://github.com/designerJordan/md-dashing-theme/archive/master.zip) and unzip this repo
* Install **Source Code Pro** and **Source Sans Pro**
* Follow the rest of the steps listed below for the app(s) of your choice 

### [LightPaper](http://clockworkengine.com/lightpaper-mac/)
---  

	~/.lightpaper/Themes/
	
* copy `md-dashing-theme/` into `~/.lightpaper/Themes/`
* Open LightPaper's Preferences
* Switch to the Styles Tab
* select **"dashing"** from the *Theme* dropdown in both the *Markdown* and *Preview* panels
* If you want to match the appearance of the example image
	* In the markdown panel
		* Set the font to **Source Code Pro**
		* Set the font-size to *16*
	
### [Marked 2](http://marked2app.com)
---  

	~/Library/Application Support/Marked/Custom CSS
	
* Open Marked 2's Preferences
* Switch to the *Style* Tab
* Click on the [+] button below the *Custom CSS* list
* Select `md-dashing-theme/dashing.css` from the location you saved it to earlier

### [Mou](http://mouapp.com)
---  

	~/Library/Application Support/Mou/CSS/
	
* copy `md-dashing-theme/dashing.css` into `~/Library/Application Support/Mou/CSS/`
* copy `md-dashing-theme/dashing.txt` into `~/Library/Application Support/Mou/Themes/`
* Open Mou's Preferences
* In the *Themes* Tab - set *Use Theme* to **"dashing"**
* In the *CSS* Tab - set *Use CSS* to **"dashing"**
    
### [QLMarkdown](https://github.com/toland/qlmarkdown)
---  

	~/Library/QuickLook/QLMarkdown.qlgenerator/Contents/Resources/style.css

* Navigate to either `/Library/QuickLook/` or `~/Library/QuickLook/` 
* Right-click/ctrl-click on `QLMarkdown.qlgenerator`
	* Select *Show Package Contents*
* Navigate to `Contents/Resources/`
* copy `md-dashing-theme/dashing.css` into the folder
* Rename `style.css` to `style-ORIG.css`
* Rename `dashing.css` to `style.css`

## Contact
Probably easiest to find me on Twitter if you feel so inclined. [@designerJordan](https://twitter.com/designerjordan)

## Mundane but Important
Dashing Theme is released under the MIT license and is copyright 2014 Jordan Pagels. The full license is located in the project repository for more information.
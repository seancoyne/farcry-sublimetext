# FarCry - Sublime Text 2
A collection of FarCry snippets for Sublime Text 2

## Installation
To install simply clone the repository into your Packages directory

```
cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages
git clone git://github.com/seancoyne/farcry-sublimetext.git FarCry
```

## Usage
There are several ways to insert a snippet.

### Menu
Tools -> Snippets...
This will display a list of snippets for your installation.  You can filter to show only the FarCry snippets by typing "FarCry"
Use the arrow keys to choose a snippet, press ENTER to insert the snippet.

### Command Palette
Tools -> Command Palette or CMD/CTRL+SHIFT+P
This will display the command palette.  To filter only snippets you can type "Snippet", or to filter only the FarCry snippets type "FarCry".
Use the arrow keys to choose a snippet, press ENTER to insert the snippet.

### Text Trigger
Many of the snippets have a text triggers.  For example, the webskin snippet is triggered by the text "webskin".  In any file if you type "webskin" (w/o quotes) then press tab the snippet will be inserted.  You can view the *.sublime-snippet files in the package to determine the trigger text.

#### Snippet Fields
Most snippets have fields where you can enter information.  When you insert the snippet your cursor will be placed at the first field.  You can enter the value then press tab to move to the next field.
The buildlink snippet is a good example.  When you insert the snippet you will see this (| is the cursor):

````cfml
<skin:buildLink objectid="|"><cfoutput></cfoutput></skin:buildLink>
`````

You can enter an objectid and press tab and you will see this:

````cfml
<skin:buildLink objectid="the object id you entered"><cfoutput>|</cfoutput></skin:buildLink>
`````

You can then enter the text for the link and press tab one last time which will move the cursor to the end of the line.

## Contributions
If you have a snippet you would like to add please [fork](https://github.com/seancoyne/farcry-sublimetext/fork) the repository and send me a pull request.
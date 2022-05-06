# AcademicTTRPG
 Bibliography of academic papers, thesis, books,... on tabletop roleplaying games. Mostly in English and French. 

## Zotero +json +GitHub

- Fork or copy this repository.
- Change the file :
  - pm.png
- Change the content of the files : 
  - index.html
  - textsInterface.json.js
- Export your references from Zotero in CSL JSON format.
  - rename it `textsGeyerCatalog.json.js`
  - edit the file and add `var catData =`  at the very beginning, before the `[`
  - Replace the file in repository by this one.
- Set up GitHub to publish webpages : Settings > Pages > Source: Main + Root + Save.

## Bugs
- Sorting by Author and Year doesn't work.

## Acknowledgements

- This code in javascript was developped by [DigitalOrientalist](https://lwcvl.github.io/RudolfGeyerCatalog/) [#](https://digitalorientalist.com/2020/12/18/turning-a-zotero-bibliography-into-an-online-browsable-catalog/) (GNU GPL 3, 2007). 

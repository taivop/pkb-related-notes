# PKB related notes
Summary of tools for automatically finding or creating notes in personal knowledge bases (PKB) -- in Roam, Obsidian, Notion, etc. This repo is just an overview and does not contain any code.

**Contributing:** I encourage you to raise an issue, or submit a PR to add links or information to work on this topic.


## Demand
* $150k bounty from the founder of Roam for a good similar-notes solution ([Twitter thread](https://twitter.com/Conaw/status/1458816332212760576)).
* Balaji Srinivasan's proposal for auto-extracting a graph out of a book/corpus ([Twitter thread](https://twitter.com/balajis/status/1307140423937265664))
* Plugin/feature requests in Obsidian forum: [1](https://forum.obsidian.md/t/connections-similar-notes-as-per-nvultra/876), [2](https://forum.obsidian.md/t/enhance-unlinked-mentions-with-similar-notes-and-similar-links/2569)

## Relevant projects
* Finding similar notes
  * Roam unlinked note finder [plugin](https://roamjs.com/extensions/unlink-finder)
  * [macedotavares/python-text-similarity](https://github.com/macedotavares/python-text-similarity): Obsidian similar notes plugin ([forum discussion](https://forum.obsidian.md/t/find-similar-notes-python-script/9450))
* Auto-extracting graphs
  * [erikrichardlarson's gist](https://gist.github.com/erikrichardlarson/a75c2d7a376733af79ab4dfd5789f670): proof-of-concept for automatic NER from text
  * [hmprt/RoamNER](https://github.com/hmprt/RoamNER) and follow-up project [RoamNERd](https://github.com/kylestratis/RoamNERd): automatic NER integration for Roam
  * [Open-Book-Genome-Project/sequencer](https://github.com/Open-Book-Genome-Project/sequencer): book processing pipeline
* Other
  * [mfarragher/obsidiantools](https://github.com/mfarragher/obsidiantools): Python package to parse Obsidian vaults. Not directly about similarity, but contains many important building blocks

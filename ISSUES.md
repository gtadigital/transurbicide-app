# easydb-output-tu
The Transurbicide Project | Known Issues
- Author: th
- Versoin 0.1 (DRAFT)


## Places
- missing Hierarchy
- added by gat Digital Data Curation Team
- to be verified https://github.com/gtadigital/transurbicide-app/issues/18 @astanicic

- missing Geo Location
- run through Wikidata and Geonames
- added geo loation from Geonames

## Taxonomy
- no Getty AAT Link added
- thus, we cannot ETL into Semantic Data
- Solution: We create our own semantic Thesaurus

## Built Work Data
###  Construction/Destruction Places 
- use an old veriosn of the field
- data will be temporarily dropped and re-aligned later -> DONE
- Built Work Avala Tower (ID 653292), has no construction place. but seems to be built in Belgrade -> construction place added
- closed https://github.com/gtadigital/transurbicide-app/issues/1

### Linked Digital Objects
- direct linking of images as implemented in EasyDB breakes the export paths (do instead of oeu)
- data in field `oeu__oeu_doc_image_transurbicide`have been temporarily dropped and re-aligned later via OpenRefine 
- link to dump https://github.com/gtadigital/transurbicide-app/files/6223012/tu_dump_images_links.zip
- closed https://github.com/gtadigital/transurbicide-app/issues/2


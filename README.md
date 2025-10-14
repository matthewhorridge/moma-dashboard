# Museum of Modern Art (MoMA) NYC Artworks Dashboard

This is a browser for the collection of the Museum of Modern Art in New York City (as of October 2025).  To view the dashboard, go [here](https://matthewhorridge.github.io/moma-dashboard).  

## Loading data

You must load some data before you can browse it.  This (currently) does not load automatically.  You can load sample data or you can load a specific [Artworks.csv](https://media.githubusercontent.com/media/MuseumofModernArt/collection/refs/heads/main/Artworks.csv) file from the [MoMA collection GitHub repository](https://github.com/MuseumofModernArt/collection).

## Examples

[Paintings by Jack Whitten](https://matthewhorridge.github.io/moma-dashboard/?load=artists&artists=Jack%2520Whitten&classes=Painting&ymin=1900&ymax=2025&page=1&pageSize=50&sortKey=title&sortDir=asc&cols=image_url%2Ctitle%2Cartist_display_name%2Cartist_nationality%2Cdepartment%2Cclassification%2Cmedium%2Cdate_text)

[Photographs in the last 5 years](https://matthewhorridge.github.io/moma-dashboard/?load=artists&classes=Photograph&ymin=2020&ymax=2025&page=1&pageSize=50&sortKey=title&sortDir=asc&cols=image_url%2Ctitle%2Cartist_display_name%2Cartist_nationality%2Cdepartment%2Cclassification%2Cmedium%2Cdate_text)

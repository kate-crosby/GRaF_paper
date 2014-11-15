GRaF_paper
==========

This is a repo for the invited piece to the special issue of AmJBot's "Evolutionary insights from studies of geographic variation". Mostly, it's a revised version of chapter 3 from my [doctoral thesis] (http://dalspace.library.dal.ca/handle/10222/55952). Sorry it's taken me this long (settling in and whatnot).

Briefly, I've added a markdown file of recommend changes from Bob Latta - and Nick, feel free to add any more. Bob is currently not on github, but I'm hoping to get him into it as that makes collaboration a tad easier.

I've also added a .gitignore for most of the rather large raster type files (which have been clipped). I've attempted to put most of these on the cluster at Dalhousie.

The folders __'scripts'__ will contain the following:

1. Script to get records from GBIF (and or other sources) - note I'm not including the spatial query to remove duplicate records, nor remove points in the sea - but that's covered here:
2. Example script to generate pseudo-absences relative to presences (this can be modified)
3. Example script to clip rasters relative to "presence/absence", and write out as clipped raster brick
4. Example script to run GRaF
5. Nick's modified function for calculating AUC

The folder __'MS'__ contains:
1. An R.md file of the paper as it currently stands
2. A script to convert this to a .docx from pandoc
3. A .md of Bob's list of recommendations that he'd like to see as re-analysis (some more crucial than others).

I should have most of these sorted by day's end. 


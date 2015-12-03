# CapMetro GTFS Health

This is just a small repo to keep track of/share results of running the [GTFS FeedValidator](https://github.com/google/transitfeed/wiki/FeedValidator) on CapMetro's GTFS data.

You can find the latest GTFS files at http://www.capmetro.org/metrolabs/

Updating the data:

```
PATH_TO_TRANSITFEED="../transitfeed/"
python $PATH_TO_TRANSITFEED/feedvalidator.py --memory_db --output=index.html --limit_per_type=99999 gtfs.zip
```

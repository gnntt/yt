# yt-dl command:

* Per scaricare singolo video Youtube:

`yt-dlp YOUTUBE-URL --format best --merge-output-format mkv --write-sub --write-thumbnail`

* Per scaricare intero canale Youtube con tutte le info:

`yt-dlp YOUTUBE-URL --format best --download-archive archive.txt --restrict-filenames --merge-output-format mkv --write-description --write-info-json --write-annotations --write-sub --write-thumbnail --ignore-errors --output '%(uploader)s/%(upload_date)s.%(title)s.%(id)s.%(ext)s'`


* Per scaricare intero canale Youtube solo video:

`yt-dlp YOUTUBE-URL --format best --download-archive archive_noe.txt --restrict-filenames --merge-output-format mkv --write-sub --write-thumbnail --ignore-errors --output '%(uploader)s/%(upload_date)s.%(title)s.%(id)s.%(ext)s'`

* Per data aggiungere:
 --datebefore 20180101

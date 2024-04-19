<h1>FileDonut<h1>
<h3>This project uses webtorrent to share files peer to peer in the browser.</h3>
* Baked up by Shyam Patel (https://github.com/shyampatell17)
* No server, it uses webtorrent trackers.
* Multyple files allowed.
* Upto 1Tb storage without server.
* Must have a good internet connection and the the browser should always be stayed on till the process of transfering ends.

## FAQ

**Where are my files sent?** Your files never touch our server. Instead, they are sent directly from the uploader's browser to the downloader's browser using WebTorrent. This requires that the uploader leave their browser window open until the transfer is complete.

**Can multiple people download my file at once?** Yes! Just send them your tempalink.

**How big can my files be?** Chrome has issues supporting files >500 MB. Firefox does not have any issues with large files, however.

**What happens when I close my browser?** The tempalink is invalidated. If a downloader has completed the transfer, that downloader will continue to seed to incomplete downloaders, but no new downloads may be initiated.

**Are my files encrypted?** Yes, all communications are automatically encrypted using public-key cryptography.

**My files are sending slowly!** Transfer speed is dependent on your network connection.


# api documentation for  [lastfmapi (v0.1.1)](https://github.com/maxkueng/node-lastfmapi)  [![npm package](https://img.shields.io/npm/v/npmdoc-lastfmapi.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-lastfmapi) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-lastfmapi.svg)](https://travis-ci.org/npmdoc/node-npmdoc-lastfmapi)
#### A Last.fm API client library wrapper with a simple and clean interface.

[![NPM](https://nodei.co/npm/lastfmapi.png?downloads=true)](https://www.npmjs.com/package/lastfmapi)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lastfmapi/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-lastfmapi_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lastfmapi/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-lastfmapi/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-lastfmapi/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Max Kueng",
        "email": "me@maxkueng.com",
        "url": "http://maxkueng.com/"
    },
    "bugs": {
        "url": "https://github.com/maxkueng/node-lastfmapi/issues"
    },
    "contributors": [
        {
            "name": "Aliou Diallo",
            "url": "https://github.com/aliou"
        },
        {
            "name": "Jiri Bakker",
            "url": "https://github.com/JiriBakker"
        }
    ],
    "dependencies": {
        "lastfm": "0.8.x"
    },
    "description": "A Last.fm API client library wrapper with a simple and clean interface.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "ce336dcf7cc81820c22dc40247c97b31133486fa",
        "tarball": "https://registry.npmjs.org/lastfmapi/-/lastfmapi-0.1.1.tgz"
    },
    "engines": {
        "node": ">=0.6.0"
    },
    "gitHead": "dfbaa253e25c4a565f918d036fec5935705bd912",
    "homepage": "https://github.com/maxkueng/node-lastfmapi",
    "keywords": [
        "lastfm",
        "audioscrobbler",
        "scrobbling",
        "scrobble",
        "api"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/maxkueng/node-lastfmapi/blob/master/LICENSE"
        }
    ],
    "main": "index",
    "maintainers": [
        {
            "name": "maxkueng",
            "email": "me@maxkueng.com"
        }
    ],
    "name": "lastfmapi",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/maxkueng/node-lastfmapi.git"
    },
    "scripts": {},
    "version": "0.1.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module lastfmapi](#apidoc.module.lastfmapi)
1.  [function <span class="apidocSignatureSpan">lastfmapi.</span>album (lastfm)](#apidoc.element.lastfmapi.album)
1.  [function <span class="apidocSignatureSpan">lastfmapi.</span>artist (lastfm)](#apidoc.element.lastfmapi.artist)
1.  [function <span class="apidocSignatureSpan">lastfmapi.</span>auth (lastfm)](#apidoc.element.lastfmapi.auth)
1.  [function <span class="apidocSignatureSpan">lastfmapi.</span>chart (lastfm)](#apidoc.element.lastfmapi.chart)
1.  [function <span class="apidocSignatureSpan">lastfmapi.</span>geo (lastfm)](#apidoc.element.lastfmapi.geo)
1.  [function <span class="apidocSignatureSpan">lastfmapi.</span>library (lastfm)](#apidoc.element.lastfmapi.library)
1.  [function <span class="apidocSignatureSpan">lastfmapi.</span>tag (lastfm)](#apidoc.element.lastfmapi.tag)
1.  [function <span class="apidocSignatureSpan">lastfmapi.</span>track (lastfm)](#apidoc.element.lastfmapi.track)
1.  [function <span class="apidocSignatureSpan">lastfmapi.</span>user (lastfm)](#apidoc.element.lastfmapi.user)
1.  object <span class="apidocSignatureSpan">lastfmapi.</span>album.prototype
1.  object <span class="apidocSignatureSpan">lastfmapi.</span>artist.prototype
1.  object <span class="apidocSignatureSpan">lastfmapi.</span>auth.prototype
1.  object <span class="apidocSignatureSpan">lastfmapi.</span>chart.prototype
1.  object <span class="apidocSignatureSpan">lastfmapi.</span>defaults
1.  object <span class="apidocSignatureSpan">lastfmapi.</span>geo.prototype
1.  object <span class="apidocSignatureSpan">lastfmapi.</span>library.prototype
1.  object <span class="apidocSignatureSpan">lastfmapi.</span>tag.prototype
1.  object <span class="apidocSignatureSpan">lastfmapi.</span>track.prototype
1.  object <span class="apidocSignatureSpan">lastfmapi.</span>user.prototype

#### [module lastfmapi.album](#apidoc.module.lastfmapi.album)
1.  [function <span class="apidocSignatureSpan">lastfmapi.</span>album (lastfm)](#apidoc.element.lastfmapi.album.album)

#### [module lastfmapi.album.prototype](#apidoc.module.lastfmapi.album.prototype)
1.  [function <span class="apidocSignatureSpan">lastfmapi.album.prototype.</span>addTags (artist, album, tags, callback)](#apidoc.element.lastfmapi.album.prototype.addTags)
1.  [function <span class="apidocSignatureSpan">lastfmapi.album.prototype.</span>getInfo (params, callback)](#apidoc.element.lastfmapi.album.prototype.getInfo)
1.  [function <span class="apidocSignatureSpan">lastfmapi.album.prototype.</span>getTags (params, callback)](#apidoc.element.lastfmapi.album.prototype.getTags)
1.  [function <span class="apidocSignatureSpan">lastfmapi.album.prototype.</span>getTopTags (params, callback)](#apidoc.element.lastfmapi.album.prototype.getTopTags)
1.  [function <span class="apidocSignatureSpan">lastfmapi.album.prototype.</span>removeTag (artist, album, tag, callback)](#apidoc.element.lastfmapi.album.prototype.removeTag)
1.  [function <span class="apidocSignatureSpan">lastfmapi.album.prototype.</span>search (params, callback)](#apidoc.element.lastfmapi.album.prototype.search)

#### [module lastfmapi.artist](#apidoc.module.lastfmapi.artist)
1.  [function <span class="apidocSignatureSpan">lastfmapi.</span>artist (lastfm)](#apidoc.element.lastfmapi.artist.artist)

#### [module lastfmapi.artist.prototype](#apidoc.module.lastfmapi.artist.prototype)
1.  [function <span class="apidocSignatureSpan">lastfmapi.artist.prototype.</span>addTags (artist, tags, callback)](#apidoc.element.lastfmapi.artist.prototype.addTags)
1.  [function <span class="apidocSignatureSpan">lastfmapi.artist.prototype.</span>getCorrection (artist, callback)](#apidoc.element.lastfmapi.artist.prototype.getCorrection)
1.  [function <span class="apidocSignatureSpan">lastfmapi.artist.prototype.</span>getInfo (params, callback)](#apidoc.element.lastfmapi.artist.prototype.getInfo)
1.  [function <span class="apidocSignatureSpan">lastfmapi.artist.prototype.</span>getSimilar (params, callback)](#apidoc.element.lastfmapi.artist.prototype.getSimilar)
1.  [function <span class="apidocSignatureSpan">lastfmapi.artist.prototype.</span>getTags (params, callback)](#apidoc.element.lastfmapi.artist.prototype.getTags)
1.  [function <span class="apidocSignatureSpan">lastfmapi.artist.prototype.</span>getTopAlbums (params, callback)](#apidoc.element.lastfmapi.artist.prototype.getTopAlbums)
1.  [function <span class="apidocSignatureSpan">lastfmapi.artist.prototype.</span>getTopTags (params, callback)](#apidoc.element.lastfmapi.artist.prototype.getTopTags)
1.  [function <span class="apidocSignatureSpan">lastfmapi.artist.prototype.</span>getTopTracks (params, callback)](#apidoc.element.lastfmapi.artist.prototype.getTopTracks)
1.  [function <span class="apidocSignatureSpan">lastfmapi.artist.prototype.</span>removeTag (artist, tag, callback)](#apidoc.element.lastfmapi.artist.prototype.removeTag)
1.  [function <span class="apidocSignatureSpan">lastfmapi.artist.prototype.</span>search (params, callback)](#apidoc.element.lastfmapi.artist.prototype.search)

#### [module lastfmapi.auth](#apidoc.module.lastfmapi.auth)
1.  [function <span class="apidocSignatureSpan">lastfmapi.</span>auth (lastfm)](#apidoc.element.lastfmapi.auth.auth)

#### [module lastfmapi.auth.prototype](#apidoc.module.lastfmapi.auth.prototype)
1.  [function <span class="apidocSignatureSpan">lastfmapi.auth.prototype.</span>getMobileSession (username, password, callback)](#apidoc.element.lastfmapi.auth.prototype.getMobileSession)
1.  [function <span class="apidocSignatureSpan">lastfmapi.auth.prototype.</span>getSession (token, callback)](#apidoc.element.lastfmapi.auth.prototype.getSession)
1.  [function <span class="apidocSignatureSpan">lastfmapi.auth.prototype.</span>getToken (callback)](#apidoc.element.lastfmapi.auth.prototype.getToken)

#### [module lastfmapi.chart](#apidoc.module.lastfmapi.chart)
1.  [function <span class="apidocSignatureSpan">lastfmapi.</span>chart (lastfm)](#apidoc.element.lastfmapi.chart.chart)

#### [module lastfmapi.chart.prototype](#apidoc.module.lastfmapi.chart.prototype)
1.  [function <span class="apidocSignatureSpan">lastfmapi.chart.prototype.</span>getLovedTracks (params, callback)](#apidoc.element.lastfmapi.chart.prototype.getLovedTracks)
1.  [function <span class="apidocSignatureSpan">lastfmapi.chart.prototype.</span>getTopArtists (params, callback)](#apidoc.element.lastfmapi.chart.prototype.getTopArtists)
1.  [function <span class="apidocSignatureSpan">lastfmapi.chart.prototype.</span>getTopTags (params, callback)](#apidoc.element.lastfmapi.chart.prototype.getTopTags)
1.  [function <span class="apidocSignatureSpan">lastfmapi.chart.prototype.</span>getTopTracks (params, callback)](#apidoc.element.lastfmapi.chart.prototype.getTopTracks)

#### [module lastfmapi.defaults](#apidoc.module.lastfmapi.defaults)
1.  [function <span class="apidocSignatureSpan">lastfmapi.defaults.</span>defaultOptions (params, callback, key)](#apidoc.element.lastfmapi.defaults.defaultOptions)

#### [module lastfmapi.geo](#apidoc.module.lastfmapi.geo)
1.  [function <span class="apidocSignatureSpan">lastfmapi.</span>geo (lastfm)](#apidoc.element.lastfmapi.geo.geo)

#### [module lastfmapi.geo.prototype](#apidoc.module.lastfmapi.geo.prototype)
1.  [function <span class="apidocSignatureSpan">lastfmapi.geo.prototype.</span>getTopArtists (params, callback)](#apidoc.element.lastfmapi.geo.prototype.getTopArtists)
1.  [function <span class="apidocSignatureSpan">lastfmapi.geo.prototype.</span>getTopTracks (params, callback)](#apidoc.element.lastfmapi.geo.prototype.getTopTracks)

#### [module lastfmapi.library](#apidoc.module.lastfmapi.library)
1.  [function <span class="apidocSignatureSpan">lastfmapi.</span>library (lastfm)](#apidoc.element.lastfmapi.library.library)

#### [module lastfmapi.library.prototype](#apidoc.module.lastfmapi.library.prototype)
1.  [function <span class="apidocSignatureSpan">lastfmapi.library.prototype.</span>getArtists (params, callback)](#apidoc.element.lastfmapi.library.prototype.getArtists)

#### [module lastfmapi.tag](#apidoc.module.lastfmapi.tag)
1.  [function <span class="apidocSignatureSpan">lastfmapi.</span>tag (lastfm)](#apidoc.element.lastfmapi.tag.tag)

#### [module lastfmapi.tag.prototype](#apidoc.module.lastfmapi.tag.prototype)
1.  [function <span class="apidocSignatureSpan">lastfmapi.tag.prototype.</span>getInfo (tag, lang, callback)](#apidoc.element.lastfmapi.tag.prototype.getInfo)
1.  [function <span class="apidocSignatureSpan">lastfmapi.tag.prototype.</span>getSimilar (tag, callback)](#apidoc.element.lastfmapi.tag.prototype.getSimilar)
1.  [function <span class="apidocSignatureSpan">lastfmapi.tag.prototype.</span>getTopAlbums (params, callback)](#apidoc.element.lastfmapi.tag.prototype.getTopAlbums)
1.  [function <span class="apidocSignatureSpan">lastfmapi.tag.prototype.</span>getTopArtists (params, callback)](#apidoc.element.lastfmapi.tag.prototype.getTopArtists)
1.  [function <span class="apidocSignatureSpan">lastfmapi.tag.prototype.</span>getTopTags (callback)](#apidoc.element.lastfmapi.tag.prototype.getTopTags)
1.  [function <span class="apidocSignatureSpan">lastfmapi.tag.prototype.</span>getTopTracks (params, callback)](#apidoc.element.lastfmapi.tag.prototype.getTopTracks)
1.  [function <span class="apidocSignatureSpan">lastfmapi.tag.prototype.</span>getWeeklyChartList (tag, callback)](#apidoc.element.lastfmapi.tag.prototype.getWeeklyChartList)

#### [module lastfmapi.track](#apidoc.module.lastfmapi.track)
1.  [function <span class="apidocSignatureSpan">lastfmapi.</span>track (lastfm)](#apidoc.element.lastfmapi.track.track)

#### [module lastfmapi.track.prototype](#apidoc.module.lastfmapi.track.prototype)
1.  [function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>addTags (artist, track, tags, callback)](#apidoc.element.lastfmapi.track.prototype.addTags)
1.  [function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>getCorrection (artist, track, callback)](#apidoc.element.lastfmapi.track.prototype.getCorrection)
1.  [function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>getInfo (params, callback)](#apidoc.element.lastfmapi.track.prototype.getInfo)
1.  [function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>getSimilar (params, callback)](#apidoc.element.lastfmapi.track.prototype.getSimilar)
1.  [function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>getTags (params, callback)](#apidoc.element.lastfmapi.track.prototype.getTags)
1.  [function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>getTopTags (params, callback)](#apidoc.element.lastfmapi.track.prototype.getTopTags)
1.  [function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>love (params, callback)](#apidoc.element.lastfmapi.track.prototype.love)
1.  [function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>removeTag (artist, track, tag, callback)](#apidoc.element.lastfmapi.track.prototype.removeTag)
1.  [function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>scrobble (params, callback)](#apidoc.element.lastfmapi.track.prototype.scrobble)
1.  [function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>search (params, callback)](#apidoc.element.lastfmapi.track.prototype.search)
1.  [function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>unlove (artist, track, callback)](#apidoc.element.lastfmapi.track.prototype.unlove)
1.  [function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>updateNowPlaying (params, callback)](#apidoc.element.lastfmapi.track.prototype.updateNowPlaying)

#### [module lastfmapi.user](#apidoc.module.lastfmapi.user)
1.  [function <span class="apidocSignatureSpan">lastfmapi.</span>user (lastfm)](#apidoc.element.lastfmapi.user.user)

#### [module lastfmapi.user.prototype](#apidoc.module.lastfmapi.user.prototype)
1.  [function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getArtistTracks (params, callback)](#apidoc.element.lastfmapi.user.prototype.getArtistTracks)
1.  [function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getFriends (params, callback)](#apidoc.element.lastfmapi.user.prototype.getFriends)
1.  [function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getInfo (user, callback)](#apidoc.element.lastfmapi.user.prototype.getInfo)
1.  [function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getLovedTracks (params, callback)](#apidoc.element.lastfmapi.user.prototype.getLovedTracks)
1.  [function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getPersonalTags (params, callback)](#apidoc.element.lastfmapi.user.prototype.getPersonalTags)
1.  [function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getRecentTracks (params, callback)](#apidoc.element.lastfmapi.user.prototype.getRecentTracks)
1.  [function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getTopAlbums (params, callback)](#apidoc.element.lastfmapi.user.prototype.getTopAlbums)
1.  [function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getTopArtists (params, callback)](#apidoc.element.lastfmapi.user.prototype.getTopArtists)
1.  [function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getTopTags (user, limit, callback)](#apidoc.element.lastfmapi.user.prototype.getTopTags)
1.  [function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getTopTracks (params, callback)](#apidoc.element.lastfmapi.user.prototype.getTopTracks)
1.  [function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getWeeklyAlbumChart (params, callback)](#apidoc.element.lastfmapi.user.prototype.getWeeklyAlbumChart)
1.  [function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getWeeklyArtistChart (params, callback)](#apidoc.element.lastfmapi.user.prototype.getWeeklyArtistChart)
1.  [function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getWeeklyChartList (user, callback)](#apidoc.element.lastfmapi.user.prototype.getWeeklyChartList)
1.  [function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getWeeklyTrackChart (params, callback)](#apidoc.element.lastfmapi.user.prototype.getWeeklyTrackChart)



# <a name="apidoc.module.lastfmapi"></a>[module lastfmapi](#apidoc.module.lastfmapi)

#### <a name="apidoc.element.lastfmapi.album"></a>[function <span class="apidocSignatureSpan">lastfmapi.</span>album (lastfm)](#apidoc.element.lastfmapi.album)
- description and source-code
```javascript
album = function (lastfm) {
	this.lastfm = lastfm;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lastfmapi.artist"></a>[function <span class="apidocSignatureSpan">lastfmapi.</span>artist (lastfm)](#apidoc.element.lastfmapi.artist)
- description and source-code
```javascript
artist = function (lastfm) {
	this.lastfm = lastfm;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lastfmapi.auth"></a>[function <span class="apidocSignatureSpan">lastfmapi.</span>auth (lastfm)](#apidoc.element.lastfmapi.auth)
- description and source-code
```javascript
auth = function (lastfm) {
	this.lastfm = lastfm;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lastfmapi.chart"></a>[function <span class="apidocSignatureSpan">lastfmapi.</span>chart (lastfm)](#apidoc.element.lastfmapi.chart)
- description and source-code
```javascript
chart = function (lastfm) {
	this.lastfm = lastfm;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lastfmapi.geo"></a>[function <span class="apidocSignatureSpan">lastfmapi.</span>geo (lastfm)](#apidoc.element.lastfmapi.geo)
- description and source-code
```javascript
geo = function (lastfm) { this.lastfm = lastfm; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lastfmapi.library"></a>[function <span class="apidocSignatureSpan">lastfmapi.</span>library (lastfm)](#apidoc.element.lastfmapi.library)
- description and source-code
```javascript
library = function (lastfm) {
	this.lastfm = lastfm;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lastfmapi.tag"></a>[function <span class="apidocSignatureSpan">lastfmapi.</span>tag (lastfm)](#apidoc.element.lastfmapi.tag)
- description and source-code
```javascript
tag = function (lastfm) {
	this.lastfm = lastfm;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lastfmapi.track"></a>[function <span class="apidocSignatureSpan">lastfmapi.</span>track (lastfm)](#apidoc.element.lastfmapi.track)
- description and source-code
```javascript
track = function (lastfm) {
	this.lastfm = lastfm;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lastfmapi.user"></a>[function <span class="apidocSignatureSpan">lastfmapi.</span>user (lastfm)](#apidoc.element.lastfmapi.user)
- description and source-code
```javascript
user = function (lastfm) {
	this.lastfm = lastfm;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lastfmapi.album"></a>[module lastfmapi.album](#apidoc.module.lastfmapi.album)

#### <a name="apidoc.element.lastfmapi.album.album"></a>[function <span class="apidocSignatureSpan">lastfmapi.</span>album (lastfm)](#apidoc.element.lastfmapi.album.album)
- description and source-code
```javascript
album = function (lastfm) {
	this.lastfm = lastfm;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lastfmapi.album.prototype"></a>[module lastfmapi.album.prototype](#apidoc.module.lastfmapi.album.prototype)

#### <a name="apidoc.element.lastfmapi.album.prototype.addTags"></a>[function <span class="apidocSignatureSpan">lastfmapi.album.prototype.</span>addTags (artist, album, tags, callback)](#apidoc.element.lastfmapi.album.prototype.addTags)
- description and source-code
```javascript
addTags = function (artist, album, tags, callback) {
	if (!Array.isArray(tags)) { tags = [ tags ]; }
	var options = defaults.defaultOptions({
		'artist' : artist,
		'album' : album,
		'tags' : tags.join(','),
		'sk' : this.lastfm.sessionCredentials.key
	}, callback);
	this.lastfm.api.request('album.addTags', options);
}
```
- example usage
```shell
...
'key' is the session key


Jump: [Album](#album) | [Artist](#artist) | [Auth](#auth) | [Chart](#chart) | [Geo](#geo) | [Library](#library) | [Tag](#tag) | [
Track](#track) | [User](#user)

### Album

##### 'lfm.album.addTags(artist, album, tags, callback(err))'

See [docs](http://www.last.fm/api/show/album.addTags). 'tags' can be a string or an array.

##### 'lfm.album.getInfo(params, callback(err, album))'

See [docs](http://www.last.fm/api/show/album.getInfo) for params.
...
```

#### <a name="apidoc.element.lastfmapi.album.prototype.getInfo"></a>[function <span class="apidocSignatureSpan">lastfmapi.album.prototype.</span>getInfo (params, callback)](#apidoc.element.lastfmapi.album.prototype.getInfo)
- description and source-code
```javascript
getInfo = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'album');
	this.lastfm.api.request('album.getInfo', options);
}
```
- example usage
```shell
...
	'secret' : 'YOUR_API_SECRET'
});
'''

Try it out:

'''javascript
lfm.track.getInfo({
	'artist' : 'Poliça',
	'track' : 'Wandering Star'
}, function (err, track) {
	if (err) { throw err; }
	console.log(track);
});
'''
...
```

#### <a name="apidoc.element.lastfmapi.album.prototype.getTags"></a>[function <span class="apidocSignatureSpan">lastfmapi.album.prototype.</span>getTags (params, callback)](#apidoc.element.lastfmapi.album.prototype.getTags)
- description and source-code
```javascript
getTags = function (params, callback) {
	if (!params.user) { params.user = this.lastfm.sessionCredentials.username; }
	var options = defaults.defaultOptions(params, callback, 'tags');
	this.lastfm.api.request('album.getTags', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/album.addTags). 'tags' can be a string or an array.

##### 'lfm.album.getInfo(params, callback(err, album))'

See [docs](http://www.last.fm/api/show/album.getInfo) for params.

##### 'lfm.album.getTags(params, callback(err, tags))'

See [docs](http://www.last.fm/api/show/album.getTags) for params.

##### 'lfm.album.getTopTags(params, callback(err, toptags))'

See [docs](http://www.last.fm/api/show/album.getTopTags) for params.
...
```

#### <a name="apidoc.element.lastfmapi.album.prototype.getTopTags"></a>[function <span class="apidocSignatureSpan">lastfmapi.album.prototype.</span>getTopTags (params, callback)](#apidoc.element.lastfmapi.album.prototype.getTopTags)
- description and source-code
```javascript
getTopTags = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'toptags');
	this.lastfm.api.request('album.getTopTags', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/album.getInfo) for params.

##### 'lfm.album.getTags(params, callback(err, tags))'

See [docs](http://www.last.fm/api/show/album.getTags) for params.

##### 'lfm.album.getTopTags(params, callback(err, toptags))'

See [docs](http://www.last.fm/api/show/album.getTopTags) for params.

##### 'lfm.album.removeTag(artist, album, tag, callback(err))'

See [docs](http://www.last.fm/api/show/album.removeTag).
...
```

#### <a name="apidoc.element.lastfmapi.album.prototype.removeTag"></a>[function <span class="apidocSignatureSpan">lastfmapi.album.prototype.</span>removeTag (artist, album, tag, callback)](#apidoc.element.lastfmapi.album.prototype.removeTag)
- description and source-code
```javascript
removeTag = function (artist, album, tag, callback) {
	var options = defaults.defaultOptions({
		'artist' : artist,
		'album' : album,
		'tag' : tag,
		'sk' : this.lastfm.sessionCredentials.key
	}, callback);
	this.lastfm.api.request('album.removeTag', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/album.getTags) for params.

##### 'lfm.album.getTopTags(params, callback(err, toptags))'

See [docs](http://www.last.fm/api/show/album.getTopTags) for params.

##### 'lfm.album.removeTag(artist, album, tag, callback(err))'

See [docs](http://www.last.fm/api/show/album.removeTag).

##### 'lfm.album.search(params, callback(err, results))'

See [docs](http://www.last.fm/api/show/album.search) for params.
...
```

#### <a name="apidoc.element.lastfmapi.album.prototype.search"></a>[function <span class="apidocSignatureSpan">lastfmapi.album.prototype.</span>search (params, callback)](#apidoc.element.lastfmapi.album.prototype.search)
- description and source-code
```javascript
search = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'results');
	this.lastfm.api.request('album.search', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/album.getTopTags) for params.

##### 'lfm.album.removeTag(artist, album, tag, callback(err))'

See [docs](http://www.last.fm/api/show/album.removeTag).

##### 'lfm.album.search(params, callback(err, results))'

See [docs](http://www.last.fm/api/show/album.search) for params.

### Artist

##### 'lfm.artist.addTags(artist, tags, callback(err))'
...
```



# <a name="apidoc.module.lastfmapi.artist"></a>[module lastfmapi.artist](#apidoc.module.lastfmapi.artist)

#### <a name="apidoc.element.lastfmapi.artist.artist"></a>[function <span class="apidocSignatureSpan">lastfmapi.</span>artist (lastfm)](#apidoc.element.lastfmapi.artist.artist)
- description and source-code
```javascript
artist = function (lastfm) {
	this.lastfm = lastfm;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lastfmapi.artist.prototype"></a>[module lastfmapi.artist.prototype](#apidoc.module.lastfmapi.artist.prototype)

#### <a name="apidoc.element.lastfmapi.artist.prototype.addTags"></a>[function <span class="apidocSignatureSpan">lastfmapi.artist.prototype.</span>addTags (artist, tags, callback)](#apidoc.element.lastfmapi.artist.prototype.addTags)
- description and source-code
```javascript
addTags = function (artist, tags, callback) {
	if (!Array.isArray(tags)) { tags = [ tags ]; }
	var options = defaults.defaultOptions({
		'artist' : artist,
		'tags' : tags.join(','),
		'sk' : this.lastfm.sessionCredentials.key
	}, callback);
	this.lastfm.api.request('artist.addTags', options);
}
```
- example usage
```shell
...
'key' is the session key


Jump: [Album](#album) | [Artist](#artist) | [Auth](#auth) | [Chart](#chart) | [Geo](#geo) | [Library](#library) | [Tag](#tag) | [
Track](#track) | [User](#user)

### Album

##### 'lfm.album.addTags(artist, album, tags, callback(err))'

See [docs](http://www.last.fm/api/show/album.addTags). 'tags' can be a string or an array.

##### 'lfm.album.getInfo(params, callback(err, album))'

See [docs](http://www.last.fm/api/show/album.getInfo) for params.
...
```

#### <a name="apidoc.element.lastfmapi.artist.prototype.getCorrection"></a>[function <span class="apidocSignatureSpan">lastfmapi.artist.prototype.</span>getCorrection (artist, callback)](#apidoc.element.lastfmapi.artist.prototype.getCorrection)
- description and source-code
```javascript
getCorrection = function (artist, callback) {
	var options = defaults.defaultOptions({ 'artist' : artist }, callback, 'corrections');
	this.lastfm.api.request('artist.getCorrection', options);
}
```
- example usage
```shell
...

### Artist

##### 'lfm.artist.addTags(artist, tags, callback(err))'

See [docs](http://www.last.fm/api/show/artist.addTags). 'tags' can be a string or an array.

##### 'lfm.artist.getCorrection(artist, callback(err, corrections))'

See [docs](http://www.last.fm/api/show/artist.getCorrection).

##### 'lfm.artist.getInfo(params, callback(err, artist))'

See [docs](http://www.last.fm/api/show/artist.getInfo) for params.
...
```

#### <a name="apidoc.element.lastfmapi.artist.prototype.getInfo"></a>[function <span class="apidocSignatureSpan">lastfmapi.artist.prototype.</span>getInfo (params, callback)](#apidoc.element.lastfmapi.artist.prototype.getInfo)
- description and source-code
```javascript
getInfo = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'artist');
	this.lastfm.api.request('artist.getInfo', options);
}
```
- example usage
```shell
...
	'secret' : 'YOUR_API_SECRET'
});
'''

Try it out:

'''javascript
lfm.track.getInfo({
	'artist' : 'Poliça',
	'track' : 'Wandering Star'
}, function (err, track) {
	if (err) { throw err; }
	console.log(track);
});
'''
...
```

#### <a name="apidoc.element.lastfmapi.artist.prototype.getSimilar"></a>[function <span class="apidocSignatureSpan">lastfmapi.artist.prototype.</span>getSimilar (params, callback)](#apidoc.element.lastfmapi.artist.prototype.getSimilar)
- description and source-code
```javascript
getSimilar = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'similarartists');
	this.lastfm.api.request('artist.getSimilar', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/artist.getCorrection).

##### 'lfm.artist.getInfo(params, callback(err, artist))'

See [docs](http://www.last.fm/api/show/artist.getInfo) for params.

##### 'lfm.artist.getSimilar(params, callback(err, similarArtists))'

See [docs](http://www.last.fm/api/show/artist.getSimilar) for params.

##### 'lfm.artist.getTags(params, callback(err, tags))'

See [docs](http://www.last.fm/api/show/artist.getTags) for params.
...
```

#### <a name="apidoc.element.lastfmapi.artist.prototype.getTags"></a>[function <span class="apidocSignatureSpan">lastfmapi.artist.prototype.</span>getTags (params, callback)](#apidoc.element.lastfmapi.artist.prototype.getTags)
- description and source-code
```javascript
getTags = function (params, callback) {
	if (!params.user) { params.user = this.lastfm.sessionCredentials.username; }
	var options = defaults.defaultOptions(params, callback, 'tags');
	this.lastfm.api.request('artist.getTags', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/album.addTags). 'tags' can be a string or an array.

##### 'lfm.album.getInfo(params, callback(err, album))'

See [docs](http://www.last.fm/api/show/album.getInfo) for params.

##### 'lfm.album.getTags(params, callback(err, tags))'

See [docs](http://www.last.fm/api/show/album.getTags) for params.

##### 'lfm.album.getTopTags(params, callback(err, toptags))'

See [docs](http://www.last.fm/api/show/album.getTopTags) for params.
...
```

#### <a name="apidoc.element.lastfmapi.artist.prototype.getTopAlbums"></a>[function <span class="apidocSignatureSpan">lastfmapi.artist.prototype.</span>getTopAlbums (params, callback)](#apidoc.element.lastfmapi.artist.prototype.getTopAlbums)
- description and source-code
```javascript
getTopAlbums = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'topalbums');
	this.lastfm.api.request('artist.getTopAlbums', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/artist.getSimilar) for params.

##### 'lfm.artist.getTags(params, callback(err, tags))'

See [docs](http://www.last.fm/api/show/artist.getTags) for params.

##### 'lfm.artist.getTopAlbums(params, callback(err, topAlbums))'

See [docs](http://www.last.fm/api/show/artist.getTopAlbums) for params.

##### 'lfm.artist.getTopTags(params, callback(err, topTags))'

See [docs](http://www.last.fm/api/show/artist.getTopTags) for params.
...
```

#### <a name="apidoc.element.lastfmapi.artist.prototype.getTopTags"></a>[function <span class="apidocSignatureSpan">lastfmapi.artist.prototype.</span>getTopTags (params, callback)](#apidoc.element.lastfmapi.artist.prototype.getTopTags)
- description and source-code
```javascript
getTopTags = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'toptags');
	this.lastfm.api.request('artist.getTopTags', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/album.getInfo) for params.

##### 'lfm.album.getTags(params, callback(err, tags))'

See [docs](http://www.last.fm/api/show/album.getTags) for params.

##### 'lfm.album.getTopTags(params, callback(err, toptags))'

See [docs](http://www.last.fm/api/show/album.getTopTags) for params.

##### 'lfm.album.removeTag(artist, album, tag, callback(err))'

See [docs](http://www.last.fm/api/show/album.removeTag).
...
```

#### <a name="apidoc.element.lastfmapi.artist.prototype.getTopTracks"></a>[function <span class="apidocSignatureSpan">lastfmapi.artist.prototype.</span>getTopTracks (params, callback)](#apidoc.element.lastfmapi.artist.prototype.getTopTracks)
- description and source-code
```javascript
getTopTracks = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'toptracks');
	this.lastfm.api.request('artist.getTopTracks', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/artist.getTopAlbums) for params.

##### 'lfm.artist.getTopTags(params, callback(err, topTags))'

See [docs](http://www.last.fm/api/show/artist.getTopTags) for params.

##### 'lfm.artist.getTopTracks(params, callback(err, topTracks))'

See [docs](http://www.last.fm/api/show/artist.getTopTracks) for params.

##### 'lfm.artist.removeTag(artist, tag, callback(err))'

See [docs](http://www.last.fm/api/show/artist.removeTag).
...
```

#### <a name="apidoc.element.lastfmapi.artist.prototype.removeTag"></a>[function <span class="apidocSignatureSpan">lastfmapi.artist.prototype.</span>removeTag (artist, tag, callback)](#apidoc.element.lastfmapi.artist.prototype.removeTag)
- description and source-code
```javascript
removeTag = function (artist, tag, callback) {
	var options = defaults.defaultOptions({
		'artist' : artist,
		'tag' : tag,
		'sk' : this.lastfm.sessionCredentials.key
	}, callback);
	this.lastfm.api.request('artist.removeTag', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/album.getTags) for params.

##### 'lfm.album.getTopTags(params, callback(err, toptags))'

See [docs](http://www.last.fm/api/show/album.getTopTags) for params.

##### 'lfm.album.removeTag(artist, album, tag, callback(err))'

See [docs](http://www.last.fm/api/show/album.removeTag).

##### 'lfm.album.search(params, callback(err, results))'

See [docs](http://www.last.fm/api/show/album.search) for params.
...
```

#### <a name="apidoc.element.lastfmapi.artist.prototype.search"></a>[function <span class="apidocSignatureSpan">lastfmapi.artist.prototype.</span>search (params, callback)](#apidoc.element.lastfmapi.artist.prototype.search)
- description and source-code
```javascript
search = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'results');
	this.lastfm.api.request('artist.search', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/album.getTopTags) for params.

##### 'lfm.album.removeTag(artist, album, tag, callback(err))'

See [docs](http://www.last.fm/api/show/album.removeTag).

##### 'lfm.album.search(params, callback(err, results))'

See [docs](http://www.last.fm/api/show/album.search) for params.

### Artist

##### 'lfm.artist.addTags(artist, tags, callback(err))'
...
```



# <a name="apidoc.module.lastfmapi.auth"></a>[module lastfmapi.auth](#apidoc.module.lastfmapi.auth)

#### <a name="apidoc.element.lastfmapi.auth.auth"></a>[function <span class="apidocSignatureSpan">lastfmapi.</span>auth (lastfm)](#apidoc.element.lastfmapi.auth.auth)
- description and source-code
```javascript
auth = function (lastfm) {
	this.lastfm = lastfm;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lastfmapi.auth.prototype"></a>[module lastfmapi.auth.prototype](#apidoc.module.lastfmapi.auth.prototype)

#### <a name="apidoc.element.lastfmapi.auth.prototype.getMobileSession"></a>[function <span class="apidocSignatureSpan">lastfmapi.auth.prototype.</span>getMobileSession (username, password, callback)](#apidoc.element.lastfmapi.auth.prototype.getMobileSession)
- description and source-code
```javascript
getMobileSession = function (username, password, callback) {
	var options = defaults.defaultOptions({
		'username' : username,
		'password' : password
	}, callback, 'session');
	this.lastfm.api.request('auth.getMobileSession', options);
}
```
- example usage
```shell
...

##### 'lfm.artist.search(params, callback(err, results))'

See [docs](http://www.last.fm/api/show/artist.search) for params.

### Auth

##### 'lfm.auth.getMobileSession(username, password, callback(err, session))'

See [docs](http://www.last.fm/api/show/auth.getMobileSession).

##### 'lfm.auth.getSession(token, callback(err, session))'

See [docs](http://www.last.fm/api/show/auth.getSession).
...
```

#### <a name="apidoc.element.lastfmapi.auth.prototype.getSession"></a>[function <span class="apidocSignatureSpan">lastfmapi.auth.prototype.</span>getSession (token, callback)](#apidoc.element.lastfmapi.auth.prototype.getSession)
- description and source-code
```javascript
getSession = function (token, callback) {
	var options = defaults.defaultOptions({ 'token' : token }, callback, 'session');
	this.lastfm.api.request('auth.getSession', options);
}
```
- example usage
```shell
...

### Auth

##### 'lfm.auth.getMobileSession(username, password, callback(err, session))'

See [docs](http://www.last.fm/api/show/auth.getMobileSession).

##### 'lfm.auth.getSession(token, callback(err, session))'

See [docs](http://www.last.fm/api/show/auth.getSession).

##### 'lfm.auth.getToken(callback(err, token))'

See [docs](http://www.last.fm/api/show/auth.getToken).
...
```

#### <a name="apidoc.element.lastfmapi.auth.prototype.getToken"></a>[function <span class="apidocSignatureSpan">lastfmapi.auth.prototype.</span>getToken (callback)](#apidoc.element.lastfmapi.auth.prototype.getToken)
- description and source-code
```javascript
getToken = function (callback) {
	var options = defaults.defaultOptions({}, callback, 'token');
	this.lastfm.api.request('auth.getToken', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/auth.getMobileSession).

##### 'lfm.auth.getSession(token, callback(err, session))'

See [docs](http://www.last.fm/api/show/auth.getSession).

##### 'lfm.auth.getToken(callback(err, token))'

See [docs](http://www.last.fm/api/show/auth.getToken).

###Chart

##### 'lfm.chart.getTopArtists([params,] callback(err, artists))'
...
```



# <a name="apidoc.module.lastfmapi.chart"></a>[module lastfmapi.chart](#apidoc.module.lastfmapi.chart)

#### <a name="apidoc.element.lastfmapi.chart.chart"></a>[function <span class="apidocSignatureSpan">lastfmapi.</span>chart (lastfm)](#apidoc.element.lastfmapi.chart.chart)
- description and source-code
```javascript
chart = function (lastfm) {
	this.lastfm = lastfm;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lastfmapi.chart.prototype"></a>[module lastfmapi.chart.prototype](#apidoc.module.lastfmapi.chart.prototype)

#### <a name="apidoc.element.lastfmapi.chart.prototype.getLovedTracks"></a>[function <span class="apidocSignatureSpan">lastfmapi.chart.prototype.</span>getLovedTracks (params, callback)](#apidoc.element.lastfmapi.chart.prototype.getLovedTracks)
- description and source-code
```javascript
getLovedTracks = function (params, callback) {
	if (typeof callback === 'undefined') { callback = params; params = null; }
	var options = defaults.defaultOptions(params, callback, 'tracks');
	this.lastfm.api.request('chart.getLovedTracks', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/user.getFriends) for params.

##### 'lfm.user.getInfo([user,] callback(err, info))'

See [docs](http://www.last.fm/api/show/user.getInfo). 'user' is optional. However, authentication is required if omitted.

##### 'lfm.user.getLovedTracks(params, callback(err, lovedTracks))'

See [docs](http://www.last.fm/api/show/user.getLovedTracks) for params.

##### 'lfm.user.getPersonalTags(params, callback(err, taggings))'

See [docs](http://www.last.fm/api/show/user.getPersonalTags) for params.
...
```

#### <a name="apidoc.element.lastfmapi.chart.prototype.getTopArtists"></a>[function <span class="apidocSignatureSpan">lastfmapi.chart.prototype.</span>getTopArtists (params, callback)](#apidoc.element.lastfmapi.chart.prototype.getTopArtists)
- description and source-code
```javascript
getTopArtists = function (params, callback) {
	if (typeof callback === 'undefined') { callback = params; params = null; }
	var options = defaults.defaultOptions(params, callback, 'artists');
	this.lastfm.api.request('chart.getTopArtists', options);
}
```
- example usage
```shell
...

##### 'lfm.auth.getToken(callback(err, token))'

See [docs](http://www.last.fm/api/show/auth.getToken).

###Chart

##### 'lfm.chart.getTopArtists([params,] callback(err, artists))'

See [docs](http://www.last.fm/api/show/chart.getTopArtists) for params. 'params' is optional.

##### 'lfm.chart.getTopTags([params,] callback(err, tags))'

See [docs](http://www.last.fm/api/show/chart.getTopTags) for params. 'params' is optional.
...
```

#### <a name="apidoc.element.lastfmapi.chart.prototype.getTopTags"></a>[function <span class="apidocSignatureSpan">lastfmapi.chart.prototype.</span>getTopTags (params, callback)](#apidoc.element.lastfmapi.chart.prototype.getTopTags)
- description and source-code
```javascript
getTopTags = function (params, callback) {
	if (typeof callback === 'undefined') { callback = params; params = null; }
	var options = defaults.defaultOptions(params, callback, 'tags');
	this.lastfm.api.request('chart.getTopTags', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/album.getInfo) for params.

##### 'lfm.album.getTags(params, callback(err, tags))'

See [docs](http://www.last.fm/api/show/album.getTags) for params.

##### 'lfm.album.getTopTags(params, callback(err, toptags))'

See [docs](http://www.last.fm/api/show/album.getTopTags) for params.

##### 'lfm.album.removeTag(artist, album, tag, callback(err))'

See [docs](http://www.last.fm/api/show/album.removeTag).
...
```

#### <a name="apidoc.element.lastfmapi.chart.prototype.getTopTracks"></a>[function <span class="apidocSignatureSpan">lastfmapi.chart.prototype.</span>getTopTracks (params, callback)](#apidoc.element.lastfmapi.chart.prototype.getTopTracks)
- description and source-code
```javascript
getTopTracks = function (params, callback) {
	if (typeof callback === 'undefined') { callback = params; params = null; }
	var options = defaults.defaultOptions(params, callback, 'tracks');
	this.lastfm.api.request('chart.getTopTracks', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/artist.getTopAlbums) for params.

##### 'lfm.artist.getTopTags(params, callback(err, topTags))'

See [docs](http://www.last.fm/api/show/artist.getTopTags) for params.

##### 'lfm.artist.getTopTracks(params, callback(err, topTracks))'

See [docs](http://www.last.fm/api/show/artist.getTopTracks) for params.

##### 'lfm.artist.removeTag(artist, tag, callback(err))'

See [docs](http://www.last.fm/api/show/artist.removeTag).
...
```



# <a name="apidoc.module.lastfmapi.defaults"></a>[module lastfmapi.defaults](#apidoc.module.lastfmapi.defaults)

#### <a name="apidoc.element.lastfmapi.defaults.defaultOptions"></a>[function <span class="apidocSignatureSpan">lastfmapi.defaults.</span>defaultOptions (params, callback, key)](#apidoc.element.lastfmapi.defaults.defaultOptions)
- description and source-code
```javascript
defaultOptions = function (params, callback, key) {
	var options = params || {};

	options.handlers = {
		'success' : function (rsp) {
			if (key) { rsp = rsp[key]; }

			if (rsp && typeof callback === 'function') {
				callback(null, rsp);
			} else {
				callback(new Error("Not found"));
			}
		},
		'error' : function (err) {
			if (typeof callback === 'function') {
				callback(err);
			}
		}
	};

	return options;
}
```
- example usage
```shell
...

var Album = module.exports = function (lastfm) {
	this.lastfm = lastfm;
};

Album.prototype.addTags = function (artist, album, tags, callback) {
	if (!Array.isArray(tags)) { tags = [ tags ]; }
	var options = defaults.defaultOptions({
		'artist' : artist,
		'album' : album,
		'tags' : tags.join(','),
		'sk' : this.lastfm.sessionCredentials.key
	}, callback);
	this.lastfm.api.request('album.addTags', options);
};
...
```



# <a name="apidoc.module.lastfmapi.geo"></a>[module lastfmapi.geo](#apidoc.module.lastfmapi.geo)

#### <a name="apidoc.element.lastfmapi.geo.geo"></a>[function <span class="apidocSignatureSpan">lastfmapi.</span>geo (lastfm)](#apidoc.element.lastfmapi.geo.geo)
- description and source-code
```javascript
geo = function (lastfm) { this.lastfm = lastfm; }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lastfmapi.geo.prototype"></a>[module lastfmapi.geo.prototype](#apidoc.module.lastfmapi.geo.prototype)

#### <a name="apidoc.element.lastfmapi.geo.prototype.getTopArtists"></a>[function <span class="apidocSignatureSpan">lastfmapi.geo.prototype.</span>getTopArtists (params, callback)](#apidoc.element.lastfmapi.geo.prototype.getTopArtists)
- description and source-code
```javascript
getTopArtists = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'topartists');
	this.lastfm.api.request('geo.getTopArtists', options);
}
```
- example usage
```shell
...

##### 'lfm.auth.getToken(callback(err, token))'

See [docs](http://www.last.fm/api/show/auth.getToken).

###Chart

##### 'lfm.chart.getTopArtists([params,] callback(err, artists))'

See [docs](http://www.last.fm/api/show/chart.getTopArtists) for params. 'params' is optional.

##### 'lfm.chart.getTopTags([params,] callback(err, tags))'

See [docs](http://www.last.fm/api/show/chart.getTopTags) for params. 'params' is optional.
...
```

#### <a name="apidoc.element.lastfmapi.geo.prototype.getTopTracks"></a>[function <span class="apidocSignatureSpan">lastfmapi.geo.prototype.</span>getTopTracks (params, callback)](#apidoc.element.lastfmapi.geo.prototype.getTopTracks)
- description and source-code
```javascript
getTopTracks = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'tracks');
	this.lastfm.api.request('geo.getTopTracks', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/artist.getTopAlbums) for params.

##### 'lfm.artist.getTopTags(params, callback(err, topTags))'

See [docs](http://www.last.fm/api/show/artist.getTopTags) for params.

##### 'lfm.artist.getTopTracks(params, callback(err, topTracks))'

See [docs](http://www.last.fm/api/show/artist.getTopTracks) for params.

##### 'lfm.artist.removeTag(artist, tag, callback(err))'

See [docs](http://www.last.fm/api/show/artist.removeTag).
...
```



# <a name="apidoc.module.lastfmapi.library"></a>[module lastfmapi.library](#apidoc.module.lastfmapi.library)

#### <a name="apidoc.element.lastfmapi.library.library"></a>[function <span class="apidocSignatureSpan">lastfmapi.</span>library (lastfm)](#apidoc.element.lastfmapi.library.library)
- description and source-code
```javascript
library = function (lastfm) {
	this.lastfm = lastfm;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lastfmapi.library.prototype"></a>[module lastfmapi.library.prototype](#apidoc.module.lastfmapi.library.prototype)

#### <a name="apidoc.element.lastfmapi.library.prototype.getArtists"></a>[function <span class="apidocSignatureSpan">lastfmapi.library.prototype.</span>getArtists (params, callback)](#apidoc.element.lastfmapi.library.prototype.getArtists)
- description and source-code
```javascript
getArtists = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'artists');
	this.lastfm.api.request('library.getArtists', options);
}
```
- example usage
```shell
...

##### 'lfm.geo.getTopTracks(params, callback(err, topTracks))'

See [docs](http://www.last.fm/api/show/geo.getTopTracks) for params.

### Library

##### 'lfm.library.getArtists(params, callback(err, artists))'

See [docs](http://www.last.fm/api/show/library.getArtists) for params.

### Tag

##### 'lfm.tag.getInfo(tag, [lang,] callback(err, tag))'
...
```



# <a name="apidoc.module.lastfmapi.tag"></a>[module lastfmapi.tag](#apidoc.module.lastfmapi.tag)

#### <a name="apidoc.element.lastfmapi.tag.tag"></a>[function <span class="apidocSignatureSpan">lastfmapi.</span>tag (lastfm)](#apidoc.element.lastfmapi.tag.tag)
- description and source-code
```javascript
tag = function (lastfm) {
	this.lastfm = lastfm;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lastfmapi.tag.prototype"></a>[module lastfmapi.tag.prototype](#apidoc.module.lastfmapi.tag.prototype)

#### <a name="apidoc.element.lastfmapi.tag.prototype.getInfo"></a>[function <span class="apidocSignatureSpan">lastfmapi.tag.prototype.</span>getInfo (tag, lang, callback)](#apidoc.element.lastfmapi.tag.prototype.getInfo)
- description and source-code
```javascript
getInfo = function (tag, lang, callback) {
	if (typeof callback !== 'function') { callback = lang; lang = null; }
	var options = defaults.defaultOptions({
		'tag' : tag,
		'lang' : lang
	}, callback, 'tag');
	this.lastfm.api.request('tag.getInfo', options);
}
```
- example usage
```shell
...
	'secret' : 'YOUR_API_SECRET'
});
'''

Try it out:

'''javascript
lfm.track.getInfo({
	'artist' : 'Poliça',
	'track' : 'Wandering Star'
}, function (err, track) {
	if (err) { throw err; }
	console.log(track);
});
'''
...
```

#### <a name="apidoc.element.lastfmapi.tag.prototype.getSimilar"></a>[function <span class="apidocSignatureSpan">lastfmapi.tag.prototype.</span>getSimilar (tag, callback)](#apidoc.element.lastfmapi.tag.prototype.getSimilar)
- description and source-code
```javascript
getSimilar = function (tag, callback) {
	var options = defaults.defaultOptions({ 'tag' : tag }, callback, 'similartags');
	this.lastfm.api.request('tag.getSimilar', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/artist.getCorrection).

##### 'lfm.artist.getInfo(params, callback(err, artist))'

See [docs](http://www.last.fm/api/show/artist.getInfo) for params.

##### 'lfm.artist.getSimilar(params, callback(err, similarArtists))'

See [docs](http://www.last.fm/api/show/artist.getSimilar) for params.

##### 'lfm.artist.getTags(params, callback(err, tags))'

See [docs](http://www.last.fm/api/show/artist.getTags) for params.
...
```

#### <a name="apidoc.element.lastfmapi.tag.prototype.getTopAlbums"></a>[function <span class="apidocSignatureSpan">lastfmapi.tag.prototype.</span>getTopAlbums (params, callback)](#apidoc.element.lastfmapi.tag.prototype.getTopAlbums)
- description and source-code
```javascript
getTopAlbums = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'topalbums');
	this.lastfm.api.request('tag.getTopAlbums', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/artist.getSimilar) for params.

##### 'lfm.artist.getTags(params, callback(err, tags))'

See [docs](http://www.last.fm/api/show/artist.getTags) for params.

##### 'lfm.artist.getTopAlbums(params, callback(err, topAlbums))'

See [docs](http://www.last.fm/api/show/artist.getTopAlbums) for params.

##### 'lfm.artist.getTopTags(params, callback(err, topTags))'

See [docs](http://www.last.fm/api/show/artist.getTopTags) for params.
...
```

#### <a name="apidoc.element.lastfmapi.tag.prototype.getTopArtists"></a>[function <span class="apidocSignatureSpan">lastfmapi.tag.prototype.</span>getTopArtists (params, callback)](#apidoc.element.lastfmapi.tag.prototype.getTopArtists)
- description and source-code
```javascript
getTopArtists = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'topartists');
	this.lastfm.api.request('tag.getTopArtists', options);
}
```
- example usage
```shell
...

##### 'lfm.auth.getToken(callback(err, token))'

See [docs](http://www.last.fm/api/show/auth.getToken).

###Chart

##### 'lfm.chart.getTopArtists([params,] callback(err, artists))'

See [docs](http://www.last.fm/api/show/chart.getTopArtists) for params. 'params' is optional.

##### 'lfm.chart.getTopTags([params,] callback(err, tags))'

See [docs](http://www.last.fm/api/show/chart.getTopTags) for params. 'params' is optional.
...
```

#### <a name="apidoc.element.lastfmapi.tag.prototype.getTopTags"></a>[function <span class="apidocSignatureSpan">lastfmapi.tag.prototype.</span>getTopTags (callback)](#apidoc.element.lastfmapi.tag.prototype.getTopTags)
- description and source-code
```javascript
getTopTags = function (callback) {
	var options = defaults.defaultOptions(null, callback, 'toptags');
	this.lastfm.api.request('tag.getTopTags', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/album.getInfo) for params.

##### 'lfm.album.getTags(params, callback(err, tags))'

See [docs](http://www.last.fm/api/show/album.getTags) for params.

##### 'lfm.album.getTopTags(params, callback(err, toptags))'

See [docs](http://www.last.fm/api/show/album.getTopTags) for params.

##### 'lfm.album.removeTag(artist, album, tag, callback(err))'

See [docs](http://www.last.fm/api/show/album.removeTag).
...
```

#### <a name="apidoc.element.lastfmapi.tag.prototype.getTopTracks"></a>[function <span class="apidocSignatureSpan">lastfmapi.tag.prototype.</span>getTopTracks (params, callback)](#apidoc.element.lastfmapi.tag.prototype.getTopTracks)
- description and source-code
```javascript
getTopTracks = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'toptracks');
	this.lastfm.api.request('tag.getTopTracks', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/artist.getTopAlbums) for params.

##### 'lfm.artist.getTopTags(params, callback(err, topTags))'

See [docs](http://www.last.fm/api/show/artist.getTopTags) for params.

##### 'lfm.artist.getTopTracks(params, callback(err, topTracks))'

See [docs](http://www.last.fm/api/show/artist.getTopTracks) for params.

##### 'lfm.artist.removeTag(artist, tag, callback(err))'

See [docs](http://www.last.fm/api/show/artist.removeTag).
...
```

#### <a name="apidoc.element.lastfmapi.tag.prototype.getWeeklyChartList"></a>[function <span class="apidocSignatureSpan">lastfmapi.tag.prototype.</span>getWeeklyChartList (tag, callback)](#apidoc.element.lastfmapi.tag.prototype.getWeeklyChartList)
- description and source-code
```javascript
getWeeklyChartList = function (tag, callback) {
	var options = defaults.defaultOptions({ 'tag' : tag }, callback, 'weeklychartlist');
	this.lastfm.api.request('tag.getWeeklyChartList', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/tag.getTopTags).

##### 'lfm.tag.getTopTracks(params, callback(err, topTracks))'

See [docs](http://www.last.fm/api/show/tag.getTopTracks) for params.

##### 'lfm.tag.getWeeklyChartList(tag, callback(err, weeklyChartList))'

See [docs](http://www.last.fm/api/show/tag.getWeeklyChartList).

### Track

##### 'lfm.track.addTags(artist, track, tags, callback(err))'
...
```



# <a name="apidoc.module.lastfmapi.track"></a>[module lastfmapi.track](#apidoc.module.lastfmapi.track)

#### <a name="apidoc.element.lastfmapi.track.track"></a>[function <span class="apidocSignatureSpan">lastfmapi.</span>track (lastfm)](#apidoc.element.lastfmapi.track.track)
- description and source-code
```javascript
track = function (lastfm) {
	this.lastfm = lastfm;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lastfmapi.track.prototype"></a>[module lastfmapi.track.prototype](#apidoc.module.lastfmapi.track.prototype)

#### <a name="apidoc.element.lastfmapi.track.prototype.addTags"></a>[function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>addTags (artist, track, tags, callback)](#apidoc.element.lastfmapi.track.prototype.addTags)
- description and source-code
```javascript
addTags = function (artist, track, tags, callback) {
	if (!Array.isArray(tags)) { tags = [ tags ]; }
	var options = defaults.defaultOptions({
		'artist' : artist,
		'track' : track,
		'tags' : tags.join(','),
		'sk' : this.lastfm.sessionCredentials.key
	}, callback);
	this.lastfm.api.request('track.addTags', options);
}
```
- example usage
```shell
...
'key' is the session key


Jump: [Album](#album) | [Artist](#artist) | [Auth](#auth) | [Chart](#chart) | [Geo](#geo) | [Library](#library) | [Tag](#tag) | [
Track](#track) | [User](#user)

### Album

##### 'lfm.album.addTags(artist, album, tags, callback(err))'

See [docs](http://www.last.fm/api/show/album.addTags). 'tags' can be a string or an array.

##### 'lfm.album.getInfo(params, callback(err, album))'

See [docs](http://www.last.fm/api/show/album.getInfo) for params.
...
```

#### <a name="apidoc.element.lastfmapi.track.prototype.getCorrection"></a>[function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>getCorrection (artist, track, callback)](#apidoc.element.lastfmapi.track.prototype.getCorrection)
- description and source-code
```javascript
getCorrection = function (artist, track, callback) {
	var options = defaults.defaultOptions({
		'artist' : artist,
		'track' : track
	}, callback, 'corrections');
	this.lastfm.api.request('track.getCorrection', options);
}
```
- example usage
```shell
...

### Artist

##### 'lfm.artist.addTags(artist, tags, callback(err))'

See [docs](http://www.last.fm/api/show/artist.addTags). 'tags' can be a string or an array.

##### 'lfm.artist.getCorrection(artist, callback(err, corrections))'

See [docs](http://www.last.fm/api/show/artist.getCorrection).

##### 'lfm.artist.getInfo(params, callback(err, artist))'

See [docs](http://www.last.fm/api/show/artist.getInfo) for params.
...
```

#### <a name="apidoc.element.lastfmapi.track.prototype.getInfo"></a>[function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>getInfo (params, callback)](#apidoc.element.lastfmapi.track.prototype.getInfo)
- description and source-code
```javascript
getInfo = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'track');
	this.lastfm.api.request('track.getInfo', options);
}
```
- example usage
```shell
...
	'secret' : 'YOUR_API_SECRET'
});
'''

Try it out:

'''javascript
lfm.track.getInfo({
	'artist' : 'Poliça',
	'track' : 'Wandering Star'
}, function (err, track) {
	if (err) { throw err; }
	console.log(track);
});
'''
...
```

#### <a name="apidoc.element.lastfmapi.track.prototype.getSimilar"></a>[function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>getSimilar (params, callback)](#apidoc.element.lastfmapi.track.prototype.getSimilar)
- description and source-code
```javascript
getSimilar = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'similartracks');
	this.lastfm.api.request('track.getSimilar', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/artist.getCorrection).

##### 'lfm.artist.getInfo(params, callback(err, artist))'

See [docs](http://www.last.fm/api/show/artist.getInfo) for params.

##### 'lfm.artist.getSimilar(params, callback(err, similarArtists))'

See [docs](http://www.last.fm/api/show/artist.getSimilar) for params.

##### 'lfm.artist.getTags(params, callback(err, tags))'

See [docs](http://www.last.fm/api/show/artist.getTags) for params.
...
```

#### <a name="apidoc.element.lastfmapi.track.prototype.getTags"></a>[function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>getTags (params, callback)](#apidoc.element.lastfmapi.track.prototype.getTags)
- description and source-code
```javascript
getTags = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'tags');
	this.lastfm.api.request('track.getTags', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/album.addTags). 'tags' can be a string or an array.

##### 'lfm.album.getInfo(params, callback(err, album))'

See [docs](http://www.last.fm/api/show/album.getInfo) for params.

##### 'lfm.album.getTags(params, callback(err, tags))'

See [docs](http://www.last.fm/api/show/album.getTags) for params.

##### 'lfm.album.getTopTags(params, callback(err, toptags))'

See [docs](http://www.last.fm/api/show/album.getTopTags) for params.
...
```

#### <a name="apidoc.element.lastfmapi.track.prototype.getTopTags"></a>[function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>getTopTags (params, callback)](#apidoc.element.lastfmapi.track.prototype.getTopTags)
- description and source-code
```javascript
getTopTags = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'toptags');
	this.lastfm.api.request('track.getTopTags', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/album.getInfo) for params.

##### 'lfm.album.getTags(params, callback(err, tags))'

See [docs](http://www.last.fm/api/show/album.getTags) for params.

##### 'lfm.album.getTopTags(params, callback(err, toptags))'

See [docs](http://www.last.fm/api/show/album.getTopTags) for params.

##### 'lfm.album.removeTag(artist, album, tag, callback(err))'

See [docs](http://www.last.fm/api/show/album.removeTag).
...
```

#### <a name="apidoc.element.lastfmapi.track.prototype.love"></a>[function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>love (params, callback)](#apidoc.element.lastfmapi.track.prototype.love)
- description and source-code
```javascript
love = function (params, callback) {
	var options = defaults.defaultOptions(params, callback);
	options.sk = this.lastfm.sessionCredentials.key;
	this.lastfm.api.request('track.love', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/track.getTags) for params.

##### 'lfm.track.getTopTags(params, callback(err, topTags))'

See [docs](http://www.last.fm/api/show/track.getTopTags) for params.

##### 'lfm.track.love(params, callback(err))'

See [docs](http://www.last.fm/api/show/track.love) for params.

##### 'lfm.track.removeTag(artist, track, tag, callback(err))'

See [docs](http://www.last.fm/api/show/track.removeTag).
...
```

#### <a name="apidoc.element.lastfmapi.track.prototype.removeTag"></a>[function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>removeTag (artist, track, tag, callback)](#apidoc.element.lastfmapi.track.prototype.removeTag)
- description and source-code
```javascript
removeTag = function (artist, track, tag, callback) {
	var options = defaults.defaultOptions({
		'artist' : artist,
		'track' : track,
		'tag' : tag,
		'sk' : this.lastfm.sessionCredentials.key
	}, callback);
	this.lastfm.api.request('track.removeTag', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/album.getTags) for params.

##### 'lfm.album.getTopTags(params, callback(err, toptags))'

See [docs](http://www.last.fm/api/show/album.getTopTags) for params.

##### 'lfm.album.removeTag(artist, album, tag, callback(err))'

See [docs](http://www.last.fm/api/show/album.removeTag).

##### 'lfm.album.search(params, callback(err, results))'

See [docs](http://www.last.fm/api/show/album.search) for params.
...
```

#### <a name="apidoc.element.lastfmapi.track.prototype.scrobble"></a>[function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>scrobble (params, callback)](#apidoc.element.lastfmapi.track.prototype.scrobble)
- description and source-code
```javascript
scrobble = function (params, callback) {
	var i, len, key, newParams = {};
	if (Array.isArray(params)) {
		for (i = 0, len = params.length; i < len; i++) {
			for (key in params[i]) {
				newParams[key + '[' + i + ']'] = params[i][key];
			}
		}
		params = newParams;
	}
	var options = defaults.defaultOptions(params, callback, 'scrobbles');
	options.sk = this.lastfm.sessionCredentials.key;
	this.lastfm.api.request('track.scrobble', options);
}
```
- example usage
```shell
...
	'username' : 'myLastFmUsername',
	'key' : 'MY_LASTFM_SESSION_KEY'
};

lfm.setSessionCredentials(mySessionCreds.username, mySessionCreds.key);

// Scrobble 'Wandering Star' by 'Poliça', 5 minutes ago
lfm.track.scrobble({
	'artist' : 'Poliça',
	'track' : 'Wandering Star',
	'timestamp' : Math.floor((new Date()).getTime() / 1000) - 300

}, function (err, scrobbles) {
	if (err) { return console.log('We\'re in trouble', err); }
...
```

#### <a name="apidoc.element.lastfmapi.track.prototype.search"></a>[function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>search (params, callback)](#apidoc.element.lastfmapi.track.prototype.search)
- description and source-code
```javascript
search = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'results');
	this.lastfm.api.request('track.search', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/album.getTopTags) for params.

##### 'lfm.album.removeTag(artist, album, tag, callback(err))'

See [docs](http://www.last.fm/api/show/album.removeTag).

##### 'lfm.album.search(params, callback(err, results))'

See [docs](http://www.last.fm/api/show/album.search) for params.

### Artist

##### 'lfm.artist.addTags(artist, tags, callback(err))'
...
```

#### <a name="apidoc.element.lastfmapi.track.prototype.unlove"></a>[function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>unlove (artist, track, callback)](#apidoc.element.lastfmapi.track.prototype.unlove)
- description and source-code
```javascript
unlove = function (artist, track, callback) {
	var options = defaults.defaultOptions({
		'artist' : artist,
		'track' : track,
		'sk' : this.lastfm.sessionCredentials.key
	}, callback);
	this.lastfm.api.request('track.unlove', options);
}
```
- example usage
```shell
...
'params' can be an array of scrobble parameters to scrobble multiple
tracks at once.

##### 'lfm.track.search(params, callback(err, results))'

See [docs](http://www.last.fm/api/show/track.search) for params.

##### 'lfm.track.unlove(artist, track, callback(err))'

See [docs](http://www.last.fm/api/show/track.unlove).

##### 'lfm.track.updateNowPlaying(params, callback(err, nowPlaying))'

See [docs](http://www.last.fm/api/show/track.updateNowPlaying) for params.
...
```

#### <a name="apidoc.element.lastfmapi.track.prototype.updateNowPlaying"></a>[function <span class="apidocSignatureSpan">lastfmapi.track.prototype.</span>updateNowPlaying (params, callback)](#apidoc.element.lastfmapi.track.prototype.updateNowPlaying)
- description and source-code
```javascript
updateNowPlaying = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'nowplaying');
	options.sk = this.lastfm.sessionCredentials.key;
	this.lastfm.api.request('track.updateNowPlaying', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/track.search) for params.

##### 'lfm.track.unlove(artist, track, callback(err))'

See [docs](http://www.last.fm/api/show/track.unlove).

##### 'lfm.track.updateNowPlaying(params, callback(err, nowPlaying))'

See [docs](http://www.last.fm/api/show/track.updateNowPlaying) for params.

### User

##### 'lfm.user.getArtistTracks(params, callback(err, artistTracks))'
...
```



# <a name="apidoc.module.lastfmapi.user"></a>[module lastfmapi.user](#apidoc.module.lastfmapi.user)

#### <a name="apidoc.element.lastfmapi.user.user"></a>[function <span class="apidocSignatureSpan">lastfmapi.</span>user (lastfm)](#apidoc.element.lastfmapi.user.user)
- description and source-code
```javascript
user = function (lastfm) {
	this.lastfm = lastfm;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lastfmapi.user.prototype"></a>[module lastfmapi.user.prototype](#apidoc.module.lastfmapi.user.prototype)

#### <a name="apidoc.element.lastfmapi.user.prototype.getArtistTracks"></a>[function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getArtistTracks (params, callback)](#apidoc.element.lastfmapi.user.prototype.getArtistTracks)
- description and source-code
```javascript
getArtistTracks = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'artisttracks');
	this.lastfm.api.request('user.getArtistTracks', options);
}
```
- example usage
```shell
...

##### 'lfm.track.updateNowPlaying(params, callback(err, nowPlaying))'

See [docs](http://www.last.fm/api/show/track.updateNowPlaying) for params.

### User

##### 'lfm.user.getArtistTracks(params, callback(err, artistTracks))'

See [docs](http://www.last.fm/api/show/user.getArtistTracks) for params.

##### 'lfm.user.getFriends(params, callback(err, friends))'

See [docs](http://www.last.fm/api/show/user.getFriends) for params.
...
```

#### <a name="apidoc.element.lastfmapi.user.prototype.getFriends"></a>[function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getFriends (params, callback)](#apidoc.element.lastfmapi.user.prototype.getFriends)
- description and source-code
```javascript
getFriends = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'friends');
	this.lastfm.api.request('user.getFriends', options);
}
```
- example usage
```shell
...

### User

##### 'lfm.user.getArtistTracks(params, callback(err, artistTracks))'

See [docs](http://www.last.fm/api/show/user.getArtistTracks) for params.

##### 'lfm.user.getFriends(params, callback(err, friends))'

See [docs](http://www.last.fm/api/show/user.getFriends) for params.

##### 'lfm.user.getInfo([user,] callback(err, info))'

See [docs](http://www.last.fm/api/show/user.getInfo). 'user' is optional. However, authentication is required if omitted.
...
```

#### <a name="apidoc.element.lastfmapi.user.prototype.getInfo"></a>[function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getInfo (user, callback)](#apidoc.element.lastfmapi.user.prototype.getInfo)
- description and source-code
```javascript
getInfo = function (user, callback) {
	if (typeof callback !== 'function') { callback = user; user = null; }
	var params = (user) ? { 'user' : user } : null;
	var options = defaults.defaultOptions(params, callback, 'user');
	if (!params) { options.sk = this.lastfm.sessionCredentials.key; }
	this.lastfm.api.request('user.getInfo', options);
}
```
- example usage
```shell
...
	'secret' : 'YOUR_API_SECRET'
});
'''

Try it out:

'''javascript
lfm.track.getInfo({
	'artist' : 'Poliça',
	'track' : 'Wandering Star'
}, function (err, track) {
	if (err) { throw err; }
	console.log(track);
});
'''
...
```

#### <a name="apidoc.element.lastfmapi.user.prototype.getLovedTracks"></a>[function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getLovedTracks (params, callback)](#apidoc.element.lastfmapi.user.prototype.getLovedTracks)
- description and source-code
```javascript
getLovedTracks = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'lovedtracks');
	this.lastfm.api.request('user.getLovedTracks', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/user.getFriends) for params.

##### 'lfm.user.getInfo([user,] callback(err, info))'

See [docs](http://www.last.fm/api/show/user.getInfo). 'user' is optional. However, authentication is required if omitted.

##### 'lfm.user.getLovedTracks(params, callback(err, lovedTracks))'

See [docs](http://www.last.fm/api/show/user.getLovedTracks) for params.

##### 'lfm.user.getPersonalTags(params, callback(err, taggings))'

See [docs](http://www.last.fm/api/show/user.getPersonalTags) for params.
...
```

#### <a name="apidoc.element.lastfmapi.user.prototype.getPersonalTags"></a>[function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getPersonalTags (params, callback)](#apidoc.element.lastfmapi.user.prototype.getPersonalTags)
- description and source-code
```javascript
getPersonalTags = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'taggings');
	this.lastfm.api.request('user.getPersonalTags', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/user.getInfo). 'user' is optional. However, authentication is required if omitted.

##### 'lfm.user.getLovedTracks(params, callback(err, lovedTracks))'

See [docs](http://www.last.fm/api/show/user.getLovedTracks) for params.

##### 'lfm.user.getPersonalTags(params, callback(err, taggings))'

See [docs](http://www.last.fm/api/show/user.getPersonalTags) for params.

##### 'lfm.user.getRecentTracks(params, callback(err, recentTracks))'

See [docs](http://www.last.fm/api/show/user.getRecentTracks) for params.
...
```

#### <a name="apidoc.element.lastfmapi.user.prototype.getRecentTracks"></a>[function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getRecentTracks (params, callback)](#apidoc.element.lastfmapi.user.prototype.getRecentTracks)
- description and source-code
```javascript
getRecentTracks = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'recenttracks');
	this.lastfm.api.request('user.getRecentTracks', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/user.getLovedTracks) for params.

##### 'lfm.user.getPersonalTags(params, callback(err, taggings))'

See [docs](http://www.last.fm/api/show/user.getPersonalTags) for params.

##### 'lfm.user.getRecentTracks(params, callback(err, recentTracks))'

See [docs](http://www.last.fm/api/show/user.getRecentTracks) for params.

##### 'lfm.user.getTopAlbums(params, callback(err, topAlbums))'

See [docs](http://www.last.fm/api/show/user.getTopAlbums) for params.
...
```

#### <a name="apidoc.element.lastfmapi.user.prototype.getTopAlbums"></a>[function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getTopAlbums (params, callback)](#apidoc.element.lastfmapi.user.prototype.getTopAlbums)
- description and source-code
```javascript
getTopAlbums = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'topalbums');
	this.lastfm.api.request('user.getTopAlbums', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/artist.getSimilar) for params.

##### 'lfm.artist.getTags(params, callback(err, tags))'

See [docs](http://www.last.fm/api/show/artist.getTags) for params.

##### 'lfm.artist.getTopAlbums(params, callback(err, topAlbums))'

See [docs](http://www.last.fm/api/show/artist.getTopAlbums) for params.

##### 'lfm.artist.getTopTags(params, callback(err, topTags))'

See [docs](http://www.last.fm/api/show/artist.getTopTags) for params.
...
```

#### <a name="apidoc.element.lastfmapi.user.prototype.getTopArtists"></a>[function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getTopArtists (params, callback)](#apidoc.element.lastfmapi.user.prototype.getTopArtists)
- description and source-code
```javascript
getTopArtists = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'topartists');
	this.lastfm.api.request('user.getTopArtists', options);
}
```
- example usage
```shell
...

##### 'lfm.auth.getToken(callback(err, token))'

See [docs](http://www.last.fm/api/show/auth.getToken).

###Chart

##### 'lfm.chart.getTopArtists([params,] callback(err, artists))'

See [docs](http://www.last.fm/api/show/chart.getTopArtists) for params. 'params' is optional.

##### 'lfm.chart.getTopTags([params,] callback(err, tags))'

See [docs](http://www.last.fm/api/show/chart.getTopTags) for params. 'params' is optional.
...
```

#### <a name="apidoc.element.lastfmapi.user.prototype.getTopTags"></a>[function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getTopTags (user, limit, callback)](#apidoc.element.lastfmapi.user.prototype.getTopTags)
- description and source-code
```javascript
getTopTags = function (user, limit, callback) {
	if (typeof callback !== 'function') { callback = limit; limit = null; }
	var options = defaults.defaultOptions({
		'user' : user,
		'limit' : limit
	}, callback, 'toptags');
	this.lastfm.api.request('user.getTopTags', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/album.getInfo) for params.

##### 'lfm.album.getTags(params, callback(err, tags))'

See [docs](http://www.last.fm/api/show/album.getTags) for params.

##### 'lfm.album.getTopTags(params, callback(err, toptags))'

See [docs](http://www.last.fm/api/show/album.getTopTags) for params.

##### 'lfm.album.removeTag(artist, album, tag, callback(err))'

See [docs](http://www.last.fm/api/show/album.removeTag).
...
```

#### <a name="apidoc.element.lastfmapi.user.prototype.getTopTracks"></a>[function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getTopTracks (params, callback)](#apidoc.element.lastfmapi.user.prototype.getTopTracks)
- description and source-code
```javascript
getTopTracks = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'toptracks');
	this.lastfm.api.request('user.getTopTracks', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/artist.getTopAlbums) for params.

##### 'lfm.artist.getTopTags(params, callback(err, topTags))'

See [docs](http://www.last.fm/api/show/artist.getTopTags) for params.

##### 'lfm.artist.getTopTracks(params, callback(err, topTracks))'

See [docs](http://www.last.fm/api/show/artist.getTopTracks) for params.

##### 'lfm.artist.removeTag(artist, tag, callback(err))'

See [docs](http://www.last.fm/api/show/artist.removeTag).
...
```

#### <a name="apidoc.element.lastfmapi.user.prototype.getWeeklyAlbumChart"></a>[function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getWeeklyAlbumChart (params, callback)](#apidoc.element.lastfmapi.user.prototype.getWeeklyAlbumChart)
- description and source-code
```javascript
getWeeklyAlbumChart = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'weeklyalbumchart');
	this.lastfm.api.request('user.getWeeklyAlbumChart', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/user.getTopTags). 'limit' is optional.

##### 'lfm.user.getTopTracks(params, callback(err, topTracks))'

See [docs](http://www.last.fm/api/show/user.getTopTracks) for params.

##### 'lfm.user.getWeeklyAlbumChart(params, callback(err, weeklyAlbumChart))'

See [docs](http://www.last.fm/api/show/user.getWeeklyAlbumChart) for params.

##### 'lfm.user.getWeeklyArtistChart(params, callback(err, weeklyArtistChart))'

See [docs](http://www.last.fm/api/show/user.getWeeklyArtistChart) for params.
...
```

#### <a name="apidoc.element.lastfmapi.user.prototype.getWeeklyArtistChart"></a>[function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getWeeklyArtistChart (params, callback)](#apidoc.element.lastfmapi.user.prototype.getWeeklyArtistChart)
- description and source-code
```javascript
getWeeklyArtistChart = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'weeklyartistchart');
	this.lastfm.api.request('user.getWeeklyArtistChart', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/user.getTopTracks) for params.

##### 'lfm.user.getWeeklyAlbumChart(params, callback(err, weeklyAlbumChart))'

See [docs](http://www.last.fm/api/show/user.getWeeklyAlbumChart) for params.

##### 'lfm.user.getWeeklyArtistChart(params, callback(err, weeklyArtistChart))'

See [docs](http://www.last.fm/api/show/user.getWeeklyArtistChart) for params.

##### 'lfm.user.getWeeklyChartList(user, callback(err, weeklyChartList))'

See [docs](http://www.last.fm/api/show/user.getWeeklyChartList).
...
```

#### <a name="apidoc.element.lastfmapi.user.prototype.getWeeklyChartList"></a>[function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getWeeklyChartList (user, callback)](#apidoc.element.lastfmapi.user.prototype.getWeeklyChartList)
- description and source-code
```javascript
getWeeklyChartList = function (user, callback) {
	var options = defaults.defaultOptions({ 'user' : user }, callback, 'weeklychartlist');
	this.lastfm.api.request('user.getWeeklyChartList', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/tag.getTopTags).

##### 'lfm.tag.getTopTracks(params, callback(err, topTracks))'

See [docs](http://www.last.fm/api/show/tag.getTopTracks) for params.

##### 'lfm.tag.getWeeklyChartList(tag, callback(err, weeklyChartList))'

See [docs](http://www.last.fm/api/show/tag.getWeeklyChartList).

### Track

##### 'lfm.track.addTags(artist, track, tags, callback(err))'
...
```

#### <a name="apidoc.element.lastfmapi.user.prototype.getWeeklyTrackChart"></a>[function <span class="apidocSignatureSpan">lastfmapi.user.prototype.</span>getWeeklyTrackChart (params, callback)](#apidoc.element.lastfmapi.user.prototype.getWeeklyTrackChart)
- description and source-code
```javascript
getWeeklyTrackChart = function (params, callback) {
	var options = defaults.defaultOptions(params, callback, 'weeklytrackchart');
	this.lastfm.api.request('user.getWeeklyTrackChart', options);
}
```
- example usage
```shell
...

See [docs](http://www.last.fm/api/show/user.getWeeklyArtistChart) for params.

##### 'lfm.user.getWeeklyChartList(user, callback(err, weeklyChartList))'

See [docs](http://www.last.fm/api/show/user.getWeeklyChartList).

##### 'lfm.user.getWeeklyTrackChart(params, callback(err, weeklyTrackChart))'

See [docs](http://www.last.fm/api/show/user.getWeeklyTrackChart) for params.

Contributors
------------

- [Max Kueng](https://github.com/maxkueng)
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

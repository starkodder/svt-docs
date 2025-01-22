# subdomains

Documentation about SVT's subdomains. 

Main domains: svt.se svtplay.se www.svtstatic.se svt-direktcenter.imgix.net tvleaks.se

# [tvleaks.se](https://tvleaks.se)
Subdomain for sharing documents with SVT "securely".

# [svt.my.salesforce-sites.com](https://svt.my.salesforce-sites.com)
Example paths: https://svt.my.salesforce-sites.com/KULprogramforslag/ https://svt.my.salesforce-sites.com/dokumentar/resource/1646662866000/DocBrief2022 https://svt.my.salesforce-sites.com/Ug/ https://svt.my.salesforce-sites.com/Nyhet

# [svtplay.se](https://svtplay.se)
### [svtplay.se](https://svtplay.se)
Used for watching movies from SVT. [Activate with code site](https://www.svtplay.se/aktivera)
### [nyhetsbrev.svtplay.se](https://nyhetsbrev.svtplay.se)
Domain for getting personalized SVTPlay newsletter, requires email verification. 
### [exp.svtplay.se](http://exp.svtplay.se)
Unknown, generates cloudflare 1001 error. 
### [www.stage.svtplay.se](http://www.stage.svtplay.se) & [stage.svtplay.se](http://stage.svtplay.se)
Returns 403, uses Akamai edgesuite. Probably staging domain for SVTPlay. 
### [auth.prod.uno.svtplay.se](https://auth.prod.uno.svtplay.se)
The path / returns 404. Used for auth on to SVTPlay, example request: POST https://auth.prod.uno.svtplay.se/authentication/v5/login/email
Data: email=john@doe.com&challenge=challenge&challengeMethod=S256 (URL encoded)
### [klipp.svtplay.se](http://klipp.svtplay.se)
Unknown, returning DNS error. 

# [www.svtstatic.se](https://www.svtstatic.se)
https://www.svtstatic.se/image/ - Image proxy

Example: https://www.svtstatic.se/image/custom/650/20992884/1549447432?format=auto&ratio=1.91

https://www.svtstatic.se/news/scribble-archive/html/{ID} - News archive of [svt.se](https://svt.se) Example ID: 2880580

https://www.svtstatic.se/resources/ - Resources
Example paths:
```text
https://www.svtstatic.se/resources/svtlib-font/fonts/PublikWeb-Regular_3.woff2
https://www.svtstatic.se/resources/svtlib-font/fonts/PublikWeb-Bold_5.woff2
https://www.svtstatic.se/resources/svtservice-n-render/svt_nyheter_2.svg
https://www.svtstatic.se/resources/svtservice-n-render/stormgeo_1.css
```
https://www.svtstatic.se/program/melodifestivalen/inbjudan-melodifestivalen-2019.pdf
https://www.svtstatic.se/program/uppdrag-granskning/11_GM-3.pdf
https://www.svtstatic.se/program/uppdrag-granskning/2_asyl-2015.pdf
https://www.svtstatic.se/program/melodifestivalen/invitation-melodifestivalen-2019-english.pdf
https://www.svtstatic.se/frontend/svtlib-font/svtlib-font-2.0.0/fonts/PublikWeb-Regular.woff2
https://www.svtstatic.se/hbbtv/smarttv/static/js/runtime-794f422fff14d4b90948.js

# [svt.se](https://svt.se)
### [svt.se](https://svt.se)
The main site, shows news articles and warnings. 

The /special path contains files or widgets for articles: 
https://www.svt.se/special/articledata/3438/datakallor-avlidna-covid19.pdf
https://www.svt.se/special/articledata/22/index.html?tMChzAFxbxrPJOsOm5T1
https://www.svt.se/special/articledata/30/vb_20231001.json
https://www.svt.se/special/articledata/2532/covid_region.json
### [svenskanyheter.svt.se](https://svenskanyheter.svt.se)
Unclear. Paths found: 
```text
https://svenskanyheter.svt.se/godareman/
https://svenskanyheter.svt.se/barnporrellerinte/
https://svenskanyheter.svt.se/downloads/ESTMEDELCutOut.pdf
https://svenskanyheter.svt.se/downloads/S-TALJE-TINGSRATT-CutOut.pdf
https://svenskanyheter.svt.se/downloads/BubblaCutOut.pdf
https://svenskanyheter.svt.se/downloads/StreckCutOut.pdf
https://svenskanyheter.svt.se/downloads/JPehrsonCutOUT.pdf
https://svenskanyheter.svt.se/assets/logo.png
```
### [vipatv.svt.se](https://vipatv.svt.se)
Unknown, redirects to [omoss.svt.se](https://omoss.svt.se).
### [reset.svt.se](https://reset.svt.se)
Site for resetting your Microsoft account password, redirects to https://passwordreset.microsoftonline.com/.  
### [hbbtv.play.svt.se](https://hbbtv.play.svt.se)
Site for viewing SVTPlay on Hybrid Broadcast Broadband TV. 
### [stage.hbbtv.play.svt.se](https://stage.hbbtv.play.svt.se)
Staging domain for HBBTV. 
### [contento.app.aws.collab.svt.se](https://contento.app.aws.collab.svt.se)
Documentation of the Contento GraphQL API. [Schema can be found here](https://contento.app.aws.collab.svt.se/contento-schema.graphqls.txt). 
### [videocollab-contento-feature.dev.borealis.svt.se](https://videocollab-contento-feature.dev.borealis.svt.se)
Documentation of another contento GraphQL API used by HBBTV, needs further investigation. 
### [vaderbild.svt.se](https://vaderbild.svt.se)
Site for uploading weatherpictures to be used in news programmes. 
### [b2b.svt.se](https://b2b.svt.se)
SVT Buisness to Buisness portal, contains design manuals for example. 
### [svtmedia.svt.se](https://svtmedia.svt.se)
Contains press material for comming shows. Needs auth. 
### [polly.svt.se](https://polly.svt.se) & [analytics.svtdesign.svt.se](https://analytics.svtdesign.svt.se)
Analytics domains. 
Example POST: https://analytics.svtdesign.svt.se/api/v1/projects/29UeLsxXy3vtkela/events

Data: type=pageview&value=/
### [pejl.svt.se](https://pejl.svt.se)
Old domain for data-driven reporting, probably used as iframes.
Example paths: 
```text
https://pejl.svt.se/kottkalkylator/
https://pejl.svt.se/brexit/
https://pejl.svt.se/ranteavdrag/
https://pejl.svt.se/zika/
https://pejl.svt.se/alkoholtillstand/
https://pejl.svt.se/ungdomsidrott/
https://pejl.svt.se/klimatguiden/
https://pejl.svt.se/elnatsavgifter/
https://pejl.svt.se/syrienflyktingar/
https://pejl.svt.se/solligan/
https://pejl.svt.se/sametingsvalet2017/
https://pejl.svt.se/min-van-tiggaren/
https://pejl.svt.se/visualisering/tag-olyckor/
https://pejl.svt.se/visualisering/inkomster/var-ar-du/
```
### [forsaken-svtstatic.app.borealis.svt.se](https://forsaken-svtstatic.app.borealis.svt.se)
Domain for data-driven reporting (probably owned by pejl), some sites are redirects from pejl.
Example paths: 
```text
https://forsaken-svtstatic.app.borealis.svt.se/pejl/dopning-i-sverige/
https://forsaken-svtstatic.app.borealis.svt.se/pejl/loneglapp/
https://forsaken-svtstatic.app.borealis.svt.se/pejl/kent/
https://forsaken-svtstatic.app.borealis.svt.se/pejl/val2014/valu-riksdag/valjarstrommar/?stripped=true
https://forsaken-svtstatic.app.borealis.svt.se/pejl/livstid/
https://forsaken-svtstatic.app.borealis.svt.se/pejl/valkompassen-sa-svarade-partierna/landstinget-i-varmland
https://forsaken-svtstatic.app.borealis.svt.se/pejl/valkompassen-sa-svarade-partierna/
```
### [auth.admin.prod.uno.svt.se](https://auth.admin.prod.uno.svt.se)
Unknown, probably admin auth. 
### [what-is-hot.dist.app.borealis.svt.se](https://what-is-hot.dist.app.borealis.svt.se) & [what-is-hot.dist.dev.borealis.svt.se](https://what-is-hot.dist.dev.borealis.svt.se)
An API for checking what is hot, docs on /, dev enpoint doesn't contain any assets, endpoints:
 - /health      # health endpoint
 - /assets      # legacy
 - /all-assets  # top 3000 assets last 2 hours
 - /isp-assets  # top 3000 assets last 24 hours
### [bookmarklet.barnplay.app.borealis.svt.se](https://bookmarklet.barnplay.app.borealis.svt.se) & [bookmarklet.barnplay.dev.borealis.svt.se](https://bookmarklet.barnplay.dev.borealis.svt.se)
A site with a bookmraklet and instructions on how to install it, bookmarklet code: https://bookmarklet.barnplay.app.borealis.svt.se/bookmarklet.js
### [42424.svt.se](https://42424.svt.se)
Remote support site, requires sessionkey (10 chars). Also has SAML bindings. 
### [contento-search.stage.svt.se](https://contento-search.stage.svt.se)
Unknown, probably for searchresults in SVTPlay, returns 403 on calling /. 
### [bookmarklet.abisko.dev.borealis.svt.se](https://bookmarklet.abisko.dev.borealis.svt.se) & [bookmarklet.abisko.app.borealis.svt.se](https://bookmarklet.abisko.app.borealis.svt.se)
Bookmarklet/JS code for doing something with abisko experiments on SVTPlay/SVTBarn sites, probably requires dev/stage enviroment. 
### [auth.vote-admin.prod.uno.svt.se](https://auth.vote-admin.prod.uno.svt.se)
Unknown, returning empty content. 
### [voting-service.barnplay.dev.borealis.svt.se](https://voting-service.barnplay.dev.borealis.svt.se) [voting-service.barnplay.app.borealis.svt.se](https://voting-service.barnplay.app.borealis.svt.se)
Unknown, returning "Not Found". 
### [vmr.svt.se](http://vmr.svt.se)
Pexip Infinity (conferencing platform). 
### [vdi.svt.se](https://vdi.svt.se)
VMWare Horizon instance. 
### [appletv3.gammalt.svt.se](https://appletv3.gammalt.svt.se)
Old appleTV v3 endpoint using XML. Paths: 
https://appletv3.gammalt.svt.se/categories/ https://appletv3.gammalt.svt.se/foryou/ https://appletv3.gammalt.svt.se/start/ https://appletv3.gammalt.svt.se/category/{category}
### [client-logger.svtplaytv.app.borealis.svt.se](https://client-logger.svtplaytv.app.borealis.svt.se)
JSON data gets POSTed to https://client-logger.svtplaytv.app.borealis.svt.se/appletv3. 
### [appletv3.svtplaytv.app.borealis.svt.se](https://appletv3.svtplaytv.app.borealis.svt.se) & [appletv3.svtplaytv.dev.borealis.svt.se](https://appletv3.svtplaytv.dev.borealis.svt.se)
New appleTV v3 endpoint using XML. Paths:  https://appletv3.svtplaytv.app.borealis.svt.se/categories/ https://appletv3.svtplaytv.app.borealis.svt.se/foryou/ https://appletv3.svtplaytv.app.borealis.svt.se/start/ https://appletv3.svtplaytv.app.borealis.svt.se/category/{category} https://appletv3.gammalt.svt.se/details/K1qBYDx/?altSorting=Default https://appletv3.gammalt.svt.se/categories/additional
### [static.gammalt.svt.se](https://static.gammalt.svt.se)
Same structure as [svtstatic.se](https://svtstatic.se), example: https://static.gammalt.svt.se/image/wide/608/51844716. 
### [australis.svt.se](https://australis.svt.se)
Sometimes used for widgets, has many subdomains. Example URLs: https://australis.svt.se/quickshot/kross/widgets/GwUSA/webframe.html https://australis.svt.se/quickshot/kross/widgets/QrY2e/webframe.html?question=Jag%20%C3%A4r%20n%C3%B6rd https://australis.svt.se/quickshot/kross/widgets/fcVlY/webframe.html https://australis.svt.se/quickshot/kross/widgets/H36fw/webframe.html?preselected=H%C3%B6st%202024 https://australis.svt.se/quickshot/kross/widgets/HEdfw/webframe.html 
### [ixpect.svtplaytv.app.borealis.svt.se](https://ixpect.svtplaytv.app.borealis.svt.se/)
Unknown, path: https://ixpect.svtplaytv.app.borealis.svt.se/settings
### [https://render.barnplay.app.borealis.svt.se](https://render.barnplay.app.borealis.svt.se/barnkanalen) & [render.barnplay.dev.borealis.svt.se](https://render.barnplay.dev.borealis.svt.se)
SVTBarn mirror, home site: https://render.barnplay.app.borealis.svt.se/barnkanalen
### [public-feature-tekniksprangarna.valkompass.dev.borealis.svt.se](https://public-feature-tekniksprangarna.valkompass.dev.borealis.svt.se)
Valkompass 2022, using NEXT.js. 
### [publikinteraktion-rpglive-svt-se.produtv.app.borealis.svt.se](https://publikinteraktion-rpglive-svt-se.produtv.app.borealis.svt.se)
Send RPG live stories to SVT. 
### [tableau.barnplay.app.borealis.svt.se/assets](https://tableau.barnplay.app.borealis.svt.se/assets)
Open directories: https://tableau.barnplay.app.borealis.svt.se/assets
### [livegrid-livegrid-duo.svtdesign.app.borealis.svt.se](https://livegrid-livegrid-duo.svtdesign.app.borealis.svt.se)
Livegrid duo camera sharing? Used for musikhjälpen.
### [livegrid.stage.svt.se/](http://livegrid.stage.svt.se/)
Livegrid instance.
### [appletv-oden.svtplaytv.dev.borealis.svt.se](https://appletv-oden.svtplaytv.dev.borealis.svt.se)
Probably AppleTV API. Endpoints: https://appletv-oden.svtplaytv.dev.borealis.svt.se/ui/index https://appletv-oden.svtplaytv.dev.borealis.svt.se/ui/tv https://appletv-oden.svtplaytv.dev.borealis.svt.se/api https://appletv-oden.svtplaytv.dev.borealis.svt.se/health
### [publikmedia-proxy.barnplay.dev.borealis.svt.se](https://publikmedia-proxy.barnplay.dev.borealis.svt.se)
Probably API/proxy. Returns "ok"
### [review-low-layout.valkompass.dev.borealis.svt.se](https://review-low-layout.valkompass.dev.borealis.svt.se)
Layout test for valkompass 2022, using NEXT.js. Example paths: https://review-low-layout.valkompass.dev.borealis.svt.se/parti/miljopartiet-de-grona-test
### [duo-webviews-feature-modalclosebutton.duo.dev.borealis.svt.se](https://duo-webviews-feature-modalclosebutton.duo.dev.borealis.svt.se)
Webviews for the DUO app, using react and lodash, example paths: https://duo-webviews-feature-modalclosebutton.duo.dev.borealis.svt.se/duo-webviews
### [siffror-stage.svt.se](https://siffror-stage.svt.se)
Statistics about usage of and value provided by SVT amongst the population. 
### [contento.svt.se](https://contento.svt.se)
SVTPlays graphql server, has introspection available and is callable at https://contento.svt.se/graphql. 
### [api.svt.se](https://api.svt.se)
One of the many APIs, has https://api.svt.se/tablatjansten/docs (Tablåtjänsten requires API key which can be obtained by sending a mail to SVT Communication) and an embed service: https://api.svt.se/videoplayer-embed/33954366 and a videoPlayer API: https://api.svt.se/videoplayer-api/video/1119767-001OA. The API also hosts a geocheck: https://api.svt.se/geocheck to check if the user qualifies for watching SVTPlay. 
### [video.svt.se](https://video.svt.se)
SVT Video API (for SVT news and SVTPlay), Example path: https://video.svt.se/video/KQn5wvW
### [valkompassen.svt.se](https://valkompassen.svt.se)
Redirecting to [valkompass.svt.se](https://valkompass.svt.se)
### [valkompass.svt.se](https://valkompass.svt.se)
SVTs voting barometer
### [appletv-version-check.svtplaytv.app.borealis.svt.se](https://appletv-version-check.svtplaytv.app.borealis.svt.se) & [appletv-version-check.svtplaytv.dev.borealis.svt.se](https://appletv-version-check.svtplaytv.dev.borealis.svt.se)
Porbably for updating and version checking for appleTV, example paths: https://appletv-version-check.svtplaytv.app.borealis.svt.se/health
### [ditto-n7s.svtplaytv.dev.borealis.svt.se](https://ditto-n7s.svtplaytv.dev.borealis.svt.se)
Unknown, probably a SVTPlay TV manifest proxy. Example paths: https://ditto-n7s.svtplaytv.dev.borealis.svt.se/health, https://ditto-n7s.svtplaytv.dev.borealis.svt.se/static (unknown, only CONNECT works)
### [nielsen-cloud-proxy.svtplaytv.dev.borealis.svt.se](https://nielsen-cloud-proxy.svtplaytv.dev.borealis.svt.se)
Unknown, probably proxy, returns: "the cloud api proxy: f0e1003". Example paths: https://nielsen-cloud-proxy.svtplaytv.dev.borealis.svt.se/log https://nielsen-cloud-proxy.svtplaytv.dev.borealis.svt.se/live
### [emoji-dashboard.barnplay.dev.borealis.svt.se](https://emoji-dashboard.barnplay.dev.borealis.svt.se)
Emoji dashboard timer test react app, used for emoji rain. 
### [info-review-jaeger-disabled.bolibompa.dev.borealis.svt.se](http://info-review-jaeger-disabled.bolibompa.dev.borealis.svt.se)
Unknown.
### [helloworld-nodejs-knative-stage.aurora.app.borealis.svt.se](http://helloworld-nodejs-knative-stage.aurora.app.borealis.svt.se/)
Unknown.
### [config.bolibompa.dev.borealis.svt.se](https://config.bolibompa.dev.borealis.svt.se)
Unknown, requires BASIC authentication. 
### [vader-vaderbilder-svt-se.produtv.dev.borealis.svt.se](https://vader-vaderbilder-svt-se.produtv.dev.borealis.svt.se) & [vader-vaderbilder-svt-se.produtv.app.borealis.svt.se](https://vader-vaderbilder-svt-se.produtv.app.borealis.svt.se)
Mirror of [vaderbild.svt.se](https://vaderbild.svt.se). 
### [svtservice-pa-sparet.duo.dev.borealis.svt.se](https://svtservice-pa-sparet.duo.dev.borealis.svt.se)
React app for the På Spåret game in the DUO app. Example paths: https://svtservice-pa-sparet.duo.dev.borealis.svt.se/assets/ https://svtservice-pa-sparet.duo.dev.borealis.svt.se/robots.txt https://svtservice-pa-sparet.duo.dev.borealis.svt.se/sounds
### [amigo.stage.uno.svt.se](https://amigo.stage.uno.svt.se)
Staging domain of the amigo API. API base URL: https://amigo.stage.uno.svt.se/amigo/v3 https://amigo.stage.uno.svt.se/amigo/demographics
### [amigo.prod.uno.svt.se](https://amigo.prod.uno.svt.se)
Production domain of the amigo API. API base URL: https://amigo.prod.uno.svt.se/amigo/v3 https://amigo.prod.uno.svt.se/amigo/demographics
### [current-time.svtplayspelare.app.borealis.svt.se](https://current-time.svtplayspelare.app.borealis.svt.se)
Returns the current time in JSON, probably for SVTPlay TV. 
### [log-receiver.dist.app.borealis.svt.se](https://log-receiver.dist.app.borealis.svt.se)
Purpose unknown, returns "hi" at route /. 
### [aretmedsvt.svt.se](https://aretmedsvt.svt.se) & [xn--retmedsvt-42a.svt.se](https://xn--retmedsvt-42a.svt.se)
A year in rewind site. 
### [video-quality-test.svt.se](https://video-quality-test.svt.se)
Video quality test site. 
### [medverka.svt.se](https://medverka.svt.se)
Site for requesting participation in SVT movies and series. 
### [sso.admin.prod.uno.svt.se](https://sso.admin.prod.uno.svt.se)
SAML Single Sign On domain. Example paths: https://sso.admin.prod.uno.svt.se/ping https://sso.admin.prod.uno.svt.se/META-INF https://sso.admin.prod.uno.svt.se/error https://sso.admin.prod.uno.svt.se/signup https://sso.admin.prod.uno.svt.se/login https://sso.admin.prod.uno.svt.se/logout https://sso.admin.prod.uno.svt.se/WEB-INF
### [stoaspprodhttp01.svt.se](https://stoaspprodhttp01.svt.se)
Unknown.
### [emoji-api.stage.duo.svt.se](https://emoji-api.stage.duo.svt.se)
Emoji guessing rebus game from the DUO app, serves JSON at /. 
### [www.playrapport.svt.se](https://www.playrapport.svt.se)
Unknown, redirects to svt.se. 
### [biathlon2008hb.svt.se](https://biathlon2008hb.svt.se)
Unknown, redirects to svt.se. 

# [oppetarkiv.se](https://oppetarkiv.se)
Archive of old SVT shows. Redirecting to https://www.svtplay.se/kategori/oppet-arkiv. 


# [svt-direktcenter.imgix.net](https://svt-direktcenter.imgix.net) & [svt-direktcenter-stage.imgix.net](https://svt-direktcenter-stage.imgix.net)
Imgix server, example img URL: https://svt-direktcenter.imgix.net/770b62921af1

# [svt-direktcenter-avatar-stage.imgix.net](https://svt-direktcenter-avatar-stage.imgix.net) & [svt-direktcenter-avatar.imgix.net](https://svt-direktcenter-avatar.imgix.net)
Imgix server, needs further research. 

# Akamaized video URL structure
https://svt-vod-7l.akamaized.net/d0/world/{DATE}20240205/{VIDEO_UUIDV4}(example: a95df091-3fca-4d40-a871-6416daf002cc) dash-lb-full.mpd hls-cmaf-full.m3u8 hls-ts-lb-full.m3u8 hls-ts-avc.m3u8 hls-cmaf-lb-full.m3u8 dash-hbbtv-avc.mpd dash-avc.mpd dash-full.mpd
Or to get a redirect wihtout needing date: https://switcher.cdn.svt.se/resolve/{VIDEO_UUIDV4}(example: a95df091-3fca-4d40-a871-6416daf002cc)/dash-lb-full.mpd

# [hbbtv-ref.azurewebsites.net](https://hbbtv-ref.azurewebsites.net)
Domain for HBBTV. Needs to be researched more. Example paths: 
https://hbbtv-ref.azurewebsites.net/catalogue/

# [media-svt.stormgeo.com](https://media-svt.stormgeo.com)
Used for weather widgets, example paths: https://media-svt.stormgeo.com/vader/133974296 https://media-svt.stormgeo.com/vader/Sylarna https://media-svt.stormgeo.com/admin/Login.aspx https://media-svt.stormgeo.com/crossdomain.xml https://media-svt.stormgeo.com/asoidioasjdoiasjdoiasjdoiasjdoiasjdoiasjd/swfobject.js https://static.stormgeo.com/widgets/map.standaardBe-2.0.css

# MISC
https://stage.hbbtv.play.svt.se/v2/index.xhtml?featureApi=true

# Social Media accounts: 
[SVT design Vimeo](https://vimeo.com/channels/669656)

# Terminology
SVTi is the team working on interactive stuff. 

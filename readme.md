Arkiv av sajten hfors.visansvanner.fi
=================================


genererad med:


```
wget --page-requisites --convert-links --adjust-extension --mirror --span-hosts --domains=hfors.visansvanner.fi http://hfors.visansvanner.fi
```

rubriken modifierad med:

```
find ./hfors-public-modified.visansvanner.fi -type f -exec sed -i -e 's/<div id="site-description">Välkommen!<\/div>/<div id="site-description" style="font-family:Tahoma, Verdana, sans-serif;color:red;line-height:1.2;">OBS: Det här är vår arkiverade hemsida från 2011 - 2021! Sidan upprätthålls inte!<br \/>Gå till vår nya hemsida på: <br\/><a href="http:\/\/helsingfors.visansvanner.fi">helsingfors.visansvanner.fi<\/a><\/div>/g' {} \;
```

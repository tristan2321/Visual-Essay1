<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Birds of America"
       author="Tristan"
       banner="https://iiif.juncture-digital.org/banner/?url=https://upload.wikimedia.org/wikipedia/commons/f/f4/Blue_jay_in_PP_%2830960%29.jpg" 
       layout="vertical">



# Blue Jay

*This* is a _blue jay_.
<param ve-image 
       url="https://tristan2321.github.io/Visual-Essay1/images/Blue_jay_in_PP_(30960).jpg">
#Bison
This is a Bison
<param ve-image
       url="https://tristan2321.github.io/Visual-Essay1/images/BigBison_EN-US4238804865_1920x1080.jpg"

# Basic usage

## Image

_Girl with a Pearl Earring_ (Dutch: Meisje met de parel) is an oil painting by Dutch Golden Age painter Johannes Vermeer, 
dated c. 1665. Going by various names over the centuries, it became known by its present title towards the end of the 
20th century after the earring worn by the girl portrayed there.[^1]
<param ve-image 
       label="Girl with a Pearl Earring" 
       description="painting by Johannes Vermeer" 
       license="public domain" 
       url="https://upload.wikimedia.org/wikipedia/commons/0/0f/1665_Girl_with_a_Pearl_Earring.jpg">

## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various 
literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Wikipedia: Girl with a Pearl Earring](https://en.wikipedia.org/wiki/Girl_with_a_Pearl_Earring)

# Test-Visual-Essay

Use this link to preview: https://juncture-digital.org/haleyrp1803/Test-Visual-Essay
juncture url / git username / name of repo

<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Basilica dei Santi Cosma e Damiano"
       author="JSTOR Labs team"
       banner="https://iiif.juncture-digital.org/banner/?url=https://upload.wikimedia.org/wikipedia/commons/a/af/Roma-basilica_cosma_e_damiano.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# Sample visual essay

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">

# Basic usage

## Image

The basilica of _Santi Cosma e Damiano_ is a titular church in Rome, Italy. The lower portion of the building is accessible through the Roman Forum and incorporates original Roman buildings, but the entrance to the upper level is outside the Forum. The circular building located at the entrance of the Forum, which now houses a small archeological exhibit, was built in the early 4th century as a Roman temple. It is thought to have been dedicated to Valerius Romulus, deified son of the emperor Maxentius. The main building was perhaps the library of an imperial forum.
<param ve-image 
       label="Basilica dei Santi Cosma e Damiano" 
       description="modern street entrance to the basilica" 
       license="Creative Commons Attribution 2.0 Generic" 
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

[^1]: [Wikipedia: Santi Cosma e Damiano](https://en.wikipedia.org/wiki/Santi_Cosma_e_Damiano)

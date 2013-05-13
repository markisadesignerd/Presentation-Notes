# RWD Review #2
---
## teehan+lax  
[Homepage]([http://www.teehanlax.com/):   

- 597k 
- 30 reqs 
- 1 image (99k)

[Story - Stackup](http://www.teehanlax.com/story/stackup/): 

- 10.5mb 
- 200 reqs 
- 165 images (9.9mb)

Ironic that there are several articles/products related to "high density" displays, but the use of high density imagery isn't consistant - some icons as fonts, most images not treated specially for "retina".

No special imlpementation for images - just CSS backgrounds and img tags.

A lot of long-flowing pages with lots of images - could benefit from lazy loading.

Stackup carousel built using [JSON](http://www.teehanlax.com/resources/json/stackup.json)

Concatinated all styles and scripts, which reduces requests. Probably a decent build script behind this to make the concatination possilble with a manageble development workflow. Nice.

Custom routing system that leverages AJAX and history pushState. No page refreshes, which means its fast.




## DiGiorno
[Homepage](http://www.digiorno.com/)

- 1.1mb
- 54 reqs
- 25 images (735kb)

[Product Page](http://www.digiorno.com/products/rising-crust/rising-crust/11152/spicy-chicken-supreme)
- 808.2kb
- 52 reqs
- 22 images (353kb)

Perfect use case for retina imagery - you want to see high-fidelity imagery for products.

<b>Updated</b> <del>jQuery in the head?</del>

Using font-face and CSS3 where possilbe. Good.

This is .NET MVC, so I'd be interested to see what's going on behind the scenes, specifically with the [Sitemap](http://www.digiorno.com/Sitemap) page.

<b>Updated</b> <del>On product page, hero shots are just img tags. Narrow viewports just get "display: none" so the 100kb image still gets downloaded.</del>

Menu open uses JS animations. Using CSS would provide a smooter transition.


## Interesting things:
[WTFMobileWeb](http://wtfmobileweb.com/post/44871479011/this-one-is-for-wtfmobileweb-would-you-like-to)  
[Picturefill - User Preference](http://lkrids.herokuapp.com/image-resizing.php)

Is it a good idea to let users choose? When is it appropriate?
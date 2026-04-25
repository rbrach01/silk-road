---
author: Rebecca Brach
title: "Coral and Carnelian Adornment at Ilibalyk, Kazakhstan"
layout: base
header-image: images/two-bracelets.png
thumbnail: images/one-bracelet.png
summary: Frequently found in association with each other, coral and carnelian are eye-catching materials of adornment.
---

# Ilibalyk, Kazakhstan

The medieval city of Ilibalyk in modern day Kazakhstan was occupied from the 10th to 15th centuries, spanning the rise and fall of the Mongol Empire. The necropolis which has been excavated over the course of ten field seasons, appears, thus far, to have a more limited period of use from approximately the 12th to 14th centuries, based on dated coins found within burials. This site is an example of a place of trade and occupation functioning within the Mongolian Empire, and later the Chagatai Khanate [Society for the Exploration of Eurasia, Switzerland et al. 2023]

The necropolis offers a window into the lives, beliefs, and culture of the occupants of the site. In particular, the majority of burials investigated thus far have cultural and stylistic markers of the Christian Church of the East, or Nestorian Christianity. Thus, the graveyard and associated finds offer a unique window into the relationship between religion and cultural identity within the wider empire. While the necropolis is limited to a subset of the population, the nearby Shahristan and city wall offer a broader view of the site’s usage and role within the region.

{% include scrollybox/bg.html
  image-path="images/coral-horde.png"
  above-box-space = "100vh"
  below-box-space = "80vh"
  box-content=' As a firmly landlocked region, the presence of coral and other exotic goods evidence far-reaching trade relationships.'
%}

In both graves in which coral has been found, it has always been in association with carnelian, and significant additional grave goods have been found. In addition, a small horde was found within the Shahristan containing one coral and two carnelian necklaces. This frequent association and presence of additional prestige goods make coral a unique perspective from which to examine the people of ancient Ilibalyk.

## In the Necropolis
{% include images/fragment-and-rings.png
class="right"
width="48%"
caption="Beads of a bracelet and rings found in a grave. [Source](https://www.exploration-eurasia.com/inhalt_english/frameset_projekt_aC.html)"
image-path="images/fragment-and-rings.png"
%}

Two graves thus far have yielded coral. Both graves were of women estimated to be middle aged, one of whom was in her final trimester of pregnancy. Additional grave goods were found with both women.


At least two rings were found in each woman's grave. One was buried with a pair of scissors, and the other with pearled earrings. Although not common, scissors have become a regular find at Ilibalyk and have been noted in both male and female graves throughout the Mongolian Empire [Society for the Exploration of Eurasia, Switzerland et al. 2023] Pearls, on the other hand, are well known as widely traded prestige goods throughout the Mongol Empire. Their beauty, natural luminescence, and association with healing properties is well documented [Allsen 2019]

[^randomthing]:Put your source information here.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus pretium, nibh vel posuere pretium, neque ipsum maximus libero, ac maximus quam ante sit amet dolor. Integer pharetra semper sem sed sagittis. Curabitur mauris tortor, elementum non felis id, hendrerit efficitur metus.


## Your First Scrollybox
Here's what makes Sapling different: keep scrolling and watch what happens next. You're about to see text appear **over** a background image, creating an immersive reading experience.

{% include scrollybox/bg.html
  image-path="images/ota-gate-khiva2.jpg"
  above-box-space = "100vh"
  below-box-space = "80vh"
  box-content=' A sculpture in Khiva offers a romaticized view of the Silk Road trade network.'
%}


## What Just Happened?
That was a **scrollybox**—text that appears in a box over a full-screen background image. As you scrolled, the background image stayed fixed while the text box scrolled into view, stayed visible, then scrolled away.

**Why use scrollyboxes?** They create moments of focus and drama. The full-screen image immerses readers in a visual context, while the overlay text provides commentary, quotations, or key points. It's like a visual pause in your narrative.

**Technical note:** The `above-box-space` and `below-box-space` parameters control how much blank scroll space appears before and after the text box. Adjust these to control pacing—more space = slower, more contemplative; less space = faster pacing.


## Pull Quotes Still Work
{% include typography/aside.html class="left" text="
This left-aligned pull quote is the same component you learned in Seedling. Sapling essays can mix scrollyboxes with traditional pull quotes depending on what fits your narrative." %}

Notice how this pull quote appears alongside regular text, while the scrollybox took over the entire screen. Different tools for different purposes:

- **Pull quotes** emphasize key text within ongoing paragraphs
- **Scrollyboxes** create immersive moments that break away from normal flow

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed consequat, lacus id blandit ornare, mi nisi rutrum ante, vitae dignissim mauris nisl mattis nisl. Praesent sed vehicula velit, vel hendrerit neque.


## Image Carousels for Comparisons
Below you'll see an **image carousel**—multiple images you can click through. This is perfect when you want readers to compare several images without cluttering the page.

{% assign images =
"images/ota-gate-demo-brown.png,
images/ota-gate-demo-gray.png,
images/ota-gate-demo-green.png" | split: ','
%}

{% include images/carousel.html
id="first"
images=images
%}

**Why use carousels?** When you have 3-5 related images (historical documents, different views of a building, a sequence of photos), a carousel lets readers compare them side-by-side without scrolling past each one. Click the arrows or dots to move between images.

**Accessibility note:** Always include captions and source links so screen readers and citations work properly.


## Larger Images
{% include images/figure.html class="right" width="60%" caption="This image is 60% width instead of 48%, giving it more visual weight. Adjust widths based on what the image needs. [Source](https://commons.wikimedia.org/wiki/File:Khiva_town_of_The_Silk_Road_(%D0%9A%D0%B0%D1%80%D0%B0%D0%B2%D0%B0%D0%BD,_%D0%98%D1%87%D0%B0%D0%BD_%D0%9A%D0%B0%D0%BB%D0%B0,_%D0%A5%D0%B8%D0%B2%D0%B0).jpg)" image-path="images/ota-gate-khiva2.jpg" %}

Just like in Seedling, you control image sizes with the `width` parameter. A floorplan or map might need 60-70% width to be legible, while a portrait might look better at 40%.

Duis ut dui dolor. Integer eu lectus at tellus accumsan euismod eget a ligula. Morbi venenatis, elit eu varius fermentum, ligula est dictum massa, sit amet ullamcorper augue nisl ut nunc.


## Block Quotes for Primary Sources
Architectural features of the Ota Darvaza reflect much of the culture of the Silk Road. Random Imaginary Person, a visitor to Khiva, spoke poetically about their experience of the architecture of the gate.

> As I entered the Ota Darvaza, the splendor of the gateway overwhelmed me. [Source](https://en.wikipedia.org/wiki/Ota_Darvaza)

Block quotes span the full text width and are perfect for extended quotations from archival sources, documents, or scholarly works. They're visually distinct from the scrollybox overlays and pull quotes.


## What You've Learned in Sapling
If you can create a Sapling essay, you can:

- **Use scrollyboxes** to overlay text on full-screen background images
- **Control pacing** with scroll space parameters
- **Add image carousels** for comparing multiple related images
- **Mix components** - scrollyboxes, pull quotes, carousels, and standard images in one essay
- **Create immersive narratives** that feel more like multimedia stories than traditional web pages

**This is enough for most sophisticated digital humanities projects.** The Forest essay adds background switching and side-scrolling for even more cinematic effects, but Sapling gives you all the tools for compelling visual scholarship.

**What makes Sapling different from Seedling?**
- Background scrollyboxes for immersive text overlays
- Image carousels for comparing multiple images
- More sophisticated visual storytelling
- All Seedling components still work

Ready for even more? Check out the [Forest template](../multilingualism-example-theme/) for advanced features like background switching and side-scrolling.

---

## Bibliography

- Allson, Thomas T. 2019. The Steppe and the Sea: Pearls in the Mongol Empire. Univeristy of Pennsylvania Press.
- Society for the Exploration of Eurasia, Switzerland, International Institute for Central Asian Studies, Archaeological Expertise LLP, Kazakhstan, and Lanier Center for Archaeology, USA. 2023. “Field Report on the Archaeological Excavations at Ilibalyk Site (Medieval Christian Necropolis), Kazakhstan in 2023.” Society for the Exploration of Eurasia, Society for the Exploration of Eurasia. https://www.exploration-eurasia.com/inhalt_english/frameset_projekt_aC.html.
- Lastname, Firstname. *Title of the Book*. Publisher Press, 1999.
+++
title = "What do we learn by studying the outer Milky Way halo?"
date = 2018-11-14T12:34:07-07:00
draft = false
#thumbnail = "img/ravsdist_radial_RRL.png"
thumbnail = "img/ravsdec_log_new.png"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []
categories = []

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
# Use `caption` to display an image caption.
#   Markdown linking is allowed, e.g. `caption = "[Image credit](http://example.org)"`.
# Set `preview` to `false` to disable the thumbnail in listings.
[header]
image = "ravsdec_log_new.png"
#image = "ravsdist_radial_RRL.png"
caption = ""
preview = true
+++

_In [my previous post]({{< ref "/post/dist_rrl.md" >}}) I discussed our project to find some of the most distant stars in the outskirts of our Milky Way galaxy. (The illustration above shows the fields on the sky that we have observed so far as part of our survey.) In this post, I'll explain more about *why* we want to find these distant Milky Way halo stars._

### Mass of the Milky Way

_We don't even know the mass of our Galaxy better than about a factor of two._ That's like if someone asked me how much I weigh, and I said "Oh, somewhere between 125 and 250 pounds." (That's about 57-113 kilograms, for those of you not used to pounds, or about 9-18 stone, if you prefer.) That's a true statement, but not very informative. We live inside the Milky Way, so it's hard to get an idea of the entire Galaxy from our perspective. It's like if you were in downtown Chicago, and you and your friends went to the observation deck of your favorite skyscraper. Do you think that by looking out over the city, you could guess how big it is and how many people live there? Sure, you could each come up with a reasonable guess, but maybe at best within a factor of two (for example, ranging between about 4.5 million to 18 million, or a factor of 2 in either direction from the Chicago metro area's population of roughly 9 million). Seems like a pretty uncertain guess, right? Well, that's how well we know the total mass of our Milky Way galaxy.

{{< figure library="1" src="img/eadie_juric2018_MW_mass_profile.png" caption="Various estimates of the mass of the Milky Way. A given study can only estimate the mass that is contained within the distance of the tracers used, so the plot above shows the mass within each radius in the Milky Way. The vertical axis is mass in units of $10^\{12}$ (trillions!) of _Solar masses_ (the mass of the Sun, a typical star). You can see that at $R =100$ kpc (_kiloparsecs_, where 100 kpc is a distance of about 325,000 light years), the estimates for our Galaxy's mass range from less than half a trillion Solar masses to as much as 1.5 trillion. This highlights just how difficult it is to measure our Galaxy's mass. (Image from [this recent paper by Eadie & Jurić (2018)](https://arxiv.org/abs/1810.10036); their best estimates for the mass are shown as shaded gray regions.)" width="80%">}}

Fine, but why does it matter whether we know our Galaxy's mass or not? First off, _because we live inside of it, the Milky Way is the best-studied galaxy in the Universe._ Because of this, we use it as a benchmark to understand other galaxies and the results of computer simulations of galaxy formation and evolution. To know which simulated galaxies to compare to, we need to know how much "stuff" (gas, stars, and dark matter -- more on that soon) our Galaxy contains.

At least half the mass of the Milky Way is in the form of _dark matter_. What is dark matter? Well, we don't know for sure, but we _do_ know that it's there. It was first definitively shown to exist in the mid-1970s by [Vera Rubin](https://en.wikipedia.org/wiki/Vera_Rubin), who measured the speed at which stars in the outer parts of nearby galaxies are rotating. The orbit of an object is determined by the amount of mass contained inside its orbit (for example, the Earth's orbit is mostly due to the Sun's gravitational influence, since the Sun makes up most of the mass in the Solar system). But when Rubin compared the rotation speeds she was measuring to what was expected due to the mass we can see (gas, dust, and stars) in the galaxies she studied, she found that all of the galaxies were rotating faster than the visible matter could account for. This means that to account for the galaxies' faster rotation, there must be some other mass present that we can't directly see -- this unseen mass is what we call "dark matter." It turns out that _dark matter makes up the majority of the mass in many (or perhaps most) galaxies_. There is a lot of other evidence for the existence of dark matter, and a lot of ongoing study to determine what it is made up of.

The reason dark matter is relevant to the discussion at hand is because it makes up most of our Galaxy's mass in the outer regions. Only 1% of the Milky Way's stars are in the halo, with most of them concentrated in the pancake-like disk of our Galaxy. Thus one of the ways to understand our Galaxy's size, mass, and shape is to use the few stars that _are_ present to study its outer parts.

{{< figure library="1" src="img/mwdwarfs_map.jpg" width="80%">}}

### Remnants of destroyed dwarf galaxies

When large galaxies like the Milky Way form, there are also smaller "dwarf galaxies" that form with them, and continue to orbit around their larger host galaxy. The image above shows an illustration of the dwarf companions of the Milky Way that were known as of about 10 years ago. We have since found many more. Dwarf galaxies are of particular interest because they have few stars, with the vast majority of their mass made up by dark matter. The number and properties of dwarf galaxies that form around each larger galaxy help us to decide between models of galaxy formation, and in particular between predictions of the properties of dark matter that makes up most of the mass. However, the dwarf galaxies that we see today don't represent _all_ of the dwarfs that the Milky Way has hosted. When these tiny galaxies approach the inner parts of their host galaxy, the stronger gravitational forces they encounter pull them apart. This is illustrated in the video shown below (from Kathryn Johnston and James Bullock), which is a computer simulation of what happens to dwarf galaxies (the colored points) as they orbit in a Milky Way-like galaxy's dark matter halo. You can see that many of them are shredded apart, and their stars become part of an overall "halo" of stars.

{{< video library="1" src="timesequence1e2.mp4" width="80%">}}

### Shape, density profile of the halo

In fact, it is thought that most of the stars in the Milky Way halo came from destroyed dwarf galaxies, and that the outermost portions of the halo are entirely made up of recently ingested dwarf galaxies. This means that by mapping the outer halo, we can infer something about the history of our galaxy. The number and properties of dwarf galaxies that have been swallowed can affect the shape of the halo (for example, if all the dwarf galaxies were concentrated to one side, the halo may look oblong). Also, the number of stars seen in the outer regions may tell us how many dwarfs fell in, and how large they were. In this way we can piece together how many dwarf galaxies were originally hosted by the Milky Way.

### Tracers of mass

Finally, as mentioned when we discussed dark matter, the motions of stars are determined by the amount of mass inside their orbit. So if we are able to measure the orbits of stars (or even of dwarf galaxies) in the Milky Way, we can use them as "tracers" to tell us how much mass is contained inside their location in our Galaxy. In the outermost Milky Way, there are very few stars, so in order to really pin down the total mass within, say, 600,000 light years, we need to find as many possible tracers as we can. This is our goal with the RR Lyrae stars -- we want to find them, then measure their motions through space, so that we can use them to determine the mass of our Galaxy. Right now, the only means we have of tracing the Galaxy's mass in the outer parts is dwarf galaxies and star clusters, of which there are very few. _This is why we need lots of RR Lyrae stars -- we don't have many tracers in the outer regions, and they're not spread out over the sky._ As mentioned in my previous post, we'll eventually find a lot of these variable stars in the outer Milky Way via LSST, but that's no reason not to look for them now! With a group of collaborators, I am doing just that -- the map at the top of this post shows the regions of sky we have searched thus far. It's painstaking work, but slowly we're building up a sample of RR Lyrae variables in the outer Galaxy with which we can probe the mass and history of the build-up of our Galaxy.

Apple iPod Hi-Fi A1121 SMPS Repair
====

Recently my iPod Hi-Fi just stopped working. No sign of life at all.
Fortunately(?) I am not alone with this situation.
[This article](http://www.whatsinside.info/apple-ipod-hi-fi-dock/) led me to suspect the power supply so I took the unit apart to take a closer look.
No signs of damaged components, but I decided to replace the big electrolytics anyway.
Just as well; they had all leaked a little (not visible until they were removed) and one of the leads had corroded right off.
That’s it, I thought.

However, when I applied power the thing still didn’t work.
After a great deal of circuit tracing, only to find all the sub-circuits working fine, I discovered that the corroded capacitor lead had also corroded the plated-through hole (PTH) that connects power to the switching regulator chip.
This, of course, was not visible when inspecting the board.
Once fixed, the unit powered up and worked just fine.

So, I have collected here the information I gathered on the journey. I hope it helps someone else restore a beautiful piece of Apple kit.

Useful Websites
----

Although now officially obsolete, Apple still has iPod Hi-Fi [FAQs]
(https://support.apple.com/en-us/HT1640)

More advice on [how to dismantle the unit]
(https://www.ifixit.com/Answers/View/125986/How+do+I+pull+one+of+these+apart)

Somebody else having a go [in pictures]
(https://www.flickr.com/photos/42224102@N06/sets/72157624734180975/with/4949551214/)

Maybe not so helpful here, but beautiful photographs at [MinimallyMinimal]
(http://www.minimallyminimal.com/blog/apple-ipod-hi-fi)

Circuit diagrams in this repo
----

Incomplete, possibly inaccurate, but hopefully enough to find your way around the power supply, a LITE-ON PA-3150-01A presumably made by LITE-ON specifically for the iPod Hi-Fi.

Health and Safety
----

At this point I should add the usual reminder that potentially lethal voltages are present in the power supply,
and will remain even after power is removed until the main capacitors are discharged. Be careful out there.
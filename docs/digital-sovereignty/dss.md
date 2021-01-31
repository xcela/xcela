---
date: 2021-01-23T07:54
---

# The Digital Sovereign Stack (DSS)

## Goal:
[[Digital sovereignty]] - self-ownership over content and community. WebTech wielded to augment the user, not exploit him. Maintaining proximity to ideals of personal computer as an exocortex and the internet as a information network. Robust and long-term stack, future-proofed and easy to archive/fork. p2p community-networked, principle of open information.

### The Gambit:
People are defined by their environment and users by their stack. Reddit doesn't attract that specific kind of limp, sheepish beta; it makes them; just as imageboards doesn;t the freewheeling shitposter, but makes them, after enough time on their platforms. If we handed new users coming online the Digital Sovereign Stack by default, and not Twitter, Facebook, Instagram, Reddit, Discord, etc.; we would build a new generation of users -- presumably one more well-minded, augmented by an external knowledge database, naturally lending themselves towards a research-orientation to fill it out, self-education chronicled in a convenient journal, and well-assisted by being networked with many others on the same mode. Ascend the network.

### Standards:
Pre-built rollout for this. Idiot-proof and minimal friction to install and setup, incl for non-coders & on Windows. Static, standards-compliant. Hosted on Github Pages[^1]. Minimal friction to update wiki and blog (markdown).

[1] Github is goal for base guide/template because (1) enforces static compliance, (2) minimizes financial overhead to go live, but most importantly: (3) makes open-source, easily forked, easily archived, version controlled data the base standard.

## The Stack

1. Personal Wiki as Public Exocortex
2. Blog -> Newsletter as Networked Journal
3. BBS/IRC as Local Town Square
4. Webring as Federation

### Personal Wiki

Must be markdown, easily generated into static html. Hypertext linking; but also some form of tree-chart navigation and generated backlinks for each page (eg list of pages that link this page). Very simple presentation that looks more like webpage articles than a "wiki".

Was experimenting with Obsidian, a text-editor designed towards acting as an exocortex; but its tools to render to html are limited.

Looking into Neuron Zettel now. How it renders pages is exactly the goal:

However the install for windows looks high friction; requires Ubuntu terminal; it seems like a lot of is operated in cli as well --- but I think it can be integrated into vim. Will experiment with the setup (is it possible to have it all rolled into one self-contained .exe?)

Fallback option would be coding up a pandoc script, so the end-user would just work in markdown (eg on Obsidian) and then run the script to render the site when ready. Would need to be robust enough that the end-user does not need to tinker in it.

Secondary comment - ideally styling would be in an easy to find, separte file for easy customization. We would also style the default template to be aesthetic.

### Blog/Newsletter
e.g. substack, but self-hosted -- ghost?

I've seen some existing options for this; issue is maintaining static & low friction setup incl on WIN. Haven't deep dived yet; hopefully we can use pre-existing solutions. It's amazing this doesn't already exist as commonplace -- Substack takes 10% cut on revenue lol.

### Static BBS

https://www.freeflarum.com/docs/faq/ ?

SomaChat/WiredNET

https://github.com/yuminaut/wired

### Webring


## Strategic Notes

Once stack is ready, I think we should present it with a nice little domain and make it as user-friendly to "install" as possible. We want as many people setting up personal websites as possible.

Full stack will be introduced to interested twitter friends; there are quite a few who are excited by the idea.

Tying into SomaChat will be more complicated. rtIRC has high potential fully on its own legs, with it tying itself back to master index of other rtIRC; and is being designed to be embeddable on sites regardless if they're DSS.

Prominent introduction of Somachat, could be through RemCo, as well as possibly Lambros?

### Urbit Pivot
Final goal: port whole DSS incl. rtIRC + rtImageboard to Urbit, possibly as a Star-specific service -- Star-specific to build a community of like-minded digital homesteaders around that star, who would be attracted across the web, not just from Urbit's circle. The DSS would be provided by default to every user that joins the star; and rtIRC and rtImageboard pre-installed. A comprehensive network.


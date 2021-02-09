---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Charge Well"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2021-02-09T11:02:45Z
lastmod: 2021-02-09T11:02:45Z
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: [ejection-charges]
---

There are many approaches to managing ejection charges for deployment ranging from rubber glove tips to machined cups. I prefer to use centrigfuge tubes, where I cut a small hole in the bottom for the e-match wires and the clip-shut cap makes sure that no powder escapes.

I have desinged a 3D printable holder for these tubes - both the smaller 1.5ml and larger 5ml sizes.

The design comprises 3 parts

* [Main Holder 5ml](/media/stl/chargewell/charge_well.stl)
* [Main Holder 1.5ml](/media/stl/chargewell/charge_well_1_5.stl)
* [Insert](/media/stl/chargewell/insert.stl)
* [Drilling Template](/media/stl/chargewell/drill_template.stl)

Installation is quite simple using the drilling template to centre punch and then drill 3x 5mm holes (for non-metal bulkheads, you can drill one 5mm hole in the centre and 2x 3mm holes for the sides). An M5 bolt is used to secure the centre of the holder (the print is threaded to accept it). When using metal bulkheads, the inserts make sure there are no shorts and reduce the 5mm holes to 3mm.

For each side, a 3mm bolt is inserted from inside the bulkhead (I use a round connector for wires to attach to the altimieter). On the holder side, a captured m3 nut secures the bolt and an brass ferrule complets the attachment assembly.

To use, the loaded tube is instered into the holder where the e-match wires will exit the side of the holder. These are simply atached to the bolt posts and secured by tghting the brass ferrules.

More details are shown in the [Ejection Charges Project](/project/ejection-charges)

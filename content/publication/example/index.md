---
title: "LEDs driven by AC without transformers or rectifiers"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Robin W Hughes
- admin


# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2021-01-01T00:00:00Z"
doi: "10.1038/s41598-020-80617-2"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Nature: Scientific Reports*
publication_short: In *Sci. Repts*

abstract: We explore the driving of LEDs by untransformed AC. An extreme case is driving 1.9 V threshold (red)
LEDs with UK mains, peak voltage 325 V. Commonly, driving is by transformed, rectified (DC) supply
with a series resistor (where a significant fraction of the power is wasted) to limit current in the LED.
With AC, one can instead reactively limit to a maximum current safe for an LED by employing a series
capacitive impedance. Cheaper and simpler supplies can thus be employed in some cases. We analyse
such non-linear circuits, and also explore questions of duty cycle and power experimentally.

# Summary. An optional shortened abstract.
summary: A reactive method of driving LEDs, quite different from the paradigm taught to students, is explored. It is highly non-linear and, at first, rather counter-intuitive.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: '(a) A series limiting resistor for a DC-driven LED to prevent excessive current greater than a failure
current. (b) The I–V characteristic of an LED is really exponential in the forward direction around Vc,
starting at a voltage Vq say. We approximate I(V) by an initially very high resistance region followed by a low
(differential) resistance R region above threshold Vc. (c) An anti-parallel pair of LEDs, L1 and L2, in series with
a capacitor C. These two LEDs could also represent two anti-parallel chains of LEDs. Conduction through L1
or L2 starts when the voltage at point a in the circuit (below the capacitor) is Vc or −Vc respectively [light lines:
A transient voltage suppressor (TVS) diode (A) in parallel with the LED chains to avoid current surges at first
switch-on].'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

# Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

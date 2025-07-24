---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: splash
author_profile: false

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: images/yosemite.png
  # actions:
  #  - label: "Download"
  #    url: "https://github.com/mmistakes/minimal-mistakes/"
  caption: ""
# excerpt: "Justin Kingsnorth's Homepage"

intro:
  - image_path: images/headshot.jpg
    alt: "placeholder image 1"
    title: "Justin Kingsnorth's Homepage"
    excerpt: "Hello! I'm a physics and mathematics concentrator in Brown University's Class of 2026. My research interests are in high energy theory, with a focus on new mathematical formulations of scattering amplitudes. I've also done work in group theory, representation theory, and condensed matter simulation. Below, you can read about my projects from the last few years.<br /><br />In my free time, I like to read and play piano! I particularly admire Kurt Vonnegut and Cedar Walton."

feature_row:
 - title: "Scattering Amplitudes in Bosonic String Theory"
   excerpt: "Will fill this in later"
 - title: "Minimal Representations and the Rubik's Cube"
   excerpt: "In the spring of 2025, I conducted research with Charles Daly on minimal faithful representations of finite groups, with the Rubik's cube as our motivation. As a first step, we determined the group structures of the 2x2 and 3x3 Rubik's cubes and showed that the 2x2 cube group embeds inside that of the 3x3. We then found minimal real and complex representations of the cube groups, and we extended our results to split extensions by abelian groups where the complementary subgroup acts faithfully by permutations. You can read more about it in [our paper](https://www.mat.uniroma2.it/~eal/Wiles-Fermat.pdf)."
 - title: "Micromagnetics Simulation"
   excerpt: "In the fall of 2024, I worked with Gang Xiao and Benjamin Brown on increasing tunneling magnetoresistance in vortex-based magnetic tunnel junctions. Using the micromagnetics package mumax3, I ran simulations of the Xiao lab's MTJs to explore the effects of various fabrication parameters on TMR. I found that decreasing the thickness of the MTJ's free layer significantly improved its sensitivity, and I also achieved some promising results by placing several MTJs in tandem."

---

 {% include feature_row id="intro" type="left" %}

 {% include feature_row %}
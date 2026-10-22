# The Machine With No Moving Parts That Sorts Rock

## Hydrocyclone classification, explained in 34 seconds — and why there is no such thing as a perfect cut

*Meta description: Hydrocyclone classification explained: how a stationary cyclone uses a vortex to split coarse and fine particles in mineral processing, why underflow returns to the grinding mill, and why no classifier achieves a perfect cut. Includes a free 34-second interactive explainer you can scrub frame by frame.*

**Tags:** Mineral Processing, Mining Engineering, Hydrocyclone, Comminution, Process Engineering

---

A hydrocyclone has no rotor. No blades, no shaft, nothing inside it turns — and yet it sorts crushed ore continuously, at tonnages that would embarrass most machines with moving parts. It does this with geometry and pressure alone.

That single fact is why hydrocyclone classification confuses people the first time they meet it, and why it rewards a proper visual explanation. This article walks through how a hydrocyclone works, why coarse and fine particles split the way they do, why the underflow goes back to the grinding mill, and — the part most diagrams skip — why the separation is never perfect. At the end you will find a free, frame-by-frame interactive explainer that shows all of it in 34 seconds.

## What Is a Hydrocyclone?

A hydrocyclone is a stationary classification device used throughout mineral processing. Picture a short cylinder sitting on top of a cone. A slurry of ground ore and water is pumped in through a tangential inlet at the top, enters the cylindrical section at speed, and begins to spiral.

Two exits leave the vessel. Coarse-biased material leaves through the apex at the bottom of the cone. That stream is the **underflow**. Fine-biased material leaves through the vortex finder at the top. That stream is the **overflow**.

There is no screen deciding what passes. There is no filter. The split happens because particles inside a vortex do not all behave the same way — and that behaviour is the whole subject of classification.

## How a Hydrocyclone Works: Two Vortices, One Vessel

Inside the cyclone, the incoming slurry forms an **outer vortex** that spirals down along the wall toward the apex. Near the axis, a second, **inner vortex** spirals upward and exits through the vortex finder. Between them sits a low-pressure air core along the centre line.

Now place a particle in that flow. A larger or denser particle experiences a stronger outward bias. It migrates toward the wall, joins the outer vortex, and reports to the underflow. A smaller or less dense particle is more easily carried by the inward and upward flow, joins the inner vortex, and reports to the overflow.

Read that again, because it contains the most common misconception in the topic: a hydrocyclone does not separate on size alone. Separation depends **jointly** on particle size, density, shape, the viscosity of the slurry, feed conditions, and the geometry of the unit. Two particles of identical size but different density can report to different outlets. That is not a malfunction. It is the physics working as designed.

## Underflow, Overflow, and the Grinding Circuit

Classification almost never stands alone. In a typical grinding circuit, the cyclone sits in closed circuit with a mill, and the two streams have opposite jobs.

The **overflow** is the fine-biased product. It moves forward to the next stage of the plant. The **underflow** is the coarse-biased stream, and it returns to the grinding mill for further size reduction. Material that has been ground again rejoins the feed and passes through the cyclone once more.

This loop is why engineers talk about circulating load. Material may travel around the mill–cyclone circuit more than once before it finally reports forward. The cyclone is effectively the gatekeeper of the circuit: it decides, particle by particle, what is finished and what goes back for more work. Understanding that gatekeeping role matters far more than memorising any single piece of equipment geometry, because the same logic appears wherever classification is used.

## The Part Most Diagrams Get Wrong: There Is No Perfect Cut

Textbook sketches often draw classification as a clean line. Everything above a certain size goes one way, everything below it goes the other. Real hydrocyclones do not work like that, and pretending they do leads to real misunderstandings about plant behaviour.

Engineers describe the split with a **partition curve**: for each particle size, the probability that a particle reports to the underflow. In an ideal world that curve would be a vertical step at the cut size. In a real cyclone it is a graded S-curve, for at least two visible reasons.

First, some fine material reports to the underflow simply because it is carried with the water that leaves through the apex, and some fine particles short-circuit the separation altogether. Second, some coarse material is misplaced to the overflow. The result is that particles near the cut size have comparable chances of leaving by either outlet, and the transition from mostly-overflow to mostly-underflow is gradual.

Any honest explainer has to show that imperfection rather than draw it away. A diagram that shows a perfect split teaches the wrong mental model, and the wrong mental model surfaces later as confusion when plant data refuses to match the sketch.

## Why a 34-Second Explainer, and Why Frame by Frame?

Classification is a causal sequence, and sequences are learned in order. So the explainer built for this article is deliberately rigid in structure. It runs exactly 34 seconds at 30 frames per second, 1,020 frames indexed from 0 to 1,019, in five acts:

1. **Frames 0–149** reveal the tangential feed, the cylindrical body, and the cone, then push in toward the active region.
2. **Frames 150–299** move to a sectional close-up of the swirling slurry, labelling only the components the mechanism actually needs.
3. **Frames 300–509** separate the coarse-biased underflow from the fine-biased overflow, keeping inputs, outputs, and control overlays visually distinct.
4. **Frames 510–749** trace the underflow back through grinding and into the feed again, with the circulating-load idea shown qualitatively.
5. **Frames 750–1019** show imperfect classification directly, misplaced particles and graded partition curve included, then pull back to a stable overview that simply holds.

Every frame is a deterministic function of its frame number. Scrubbing, stepping one frame at a time, and replaying all show exactly the same state. That matters for teaching: an instructor can stop on the precise frame where a coarse particle commits to the wall, or where a fine particle turns into the inner vortex, and the class is all looking at the same thing.

The explainer also observes a discipline that technical content online often skips. It invents nothing. There are no dimensions, no operating settings, no efficiencies, no recovery figures, and no vendor internals, because none were supplied as data. The graphs are labelled qualitative. The mass bar uses 100 conceptual units to show conservation — feed equals overflow plus underflow — and is labelled as exactly that, not as plant data. Changed scale, slow motion, and time compression are labelled on screen. What you are looking at is a labelled conceptual schematic, and it says so in every frame.

## What to Take Away

If you remember four things, remember these.

A hydrocyclone is a stationary vessel. The vortex, not a rotor, does the work. Particles split because size, density, shape, slurry conditions, and geometry act on them together inside that vortex — never because of size alone. The underflow returns to grinding while the overflow moves forward, which makes the cyclone the gatekeeper of the grinding circuit. And the cut is a probability curve, not a line: some fines always leave with the underflow, some coarse can be misplaced to the overflow, and no real classifier achieves a perfect separation.

Hold those four ideas and most hydrocyclone behaviour you will ever meet stops being surprising.

## Watch It, Then Share It

The interactive explainer is free to open in any browser, with no build step and no dependencies:

**Live explainer:** https://mizcausevic-dev.github.io/hydrocyclone-classification-explainer/anatomy-explainer-Cursor.html
**Source code:** https://github.com/mizcausevic-dev/hydrocyclone-classification-explainer

Open it, scrub to frame 400 and watch one coarse particle commit to the apex and one fine particle turn up the centre, then jump to the final act and look for the misplaced particles the diagram refuses to hide. If you teach, train operators, or onboard engineers into mineral processing, steal the five-act structure. It transfers intact to screens, spirals, and centrifuges, because every classifier tells the same five-part story: reveal the vessel, show the field, split the streams, close the loop, and admit the imperfection.

That honesty is the point. The best technical explanations do not just show how a mechanism works when it behaves. They show where it leaks, what it cannot decide, and what it never promised. A hydrocyclone never promised a perfect cut. Now you can watch it keep exactly the promise it did make.

---

*The explainer is a conceptual schematic for education. It is not a certified design, a simulation result, operating guidance, or a claim about any specific commercial unit. For real plant work, follow site procedures, OEM documentation, and competent supervision. Mechanism background: Minerals Engineering, hydrocyclone classification (ScienceDirect S0892687524000414). Camera, palette, cutaways, and timing in the explainer are original illustrative direction.*

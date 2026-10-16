---
SG90 Robot Arm
Oliver Ueno
Designing, printing, and testing an SG90 robot arm.
2026-07-24
---

# July 24, 2026: Designing the fixed base

I tested the servos and picked four that worked well. I started with a small printed gauge to check how the servo body would fit. The first opening was too loose, so I measured the body again and got about 23.1 × 12.1 mm. I changed the opening and tried another print.

I also made the fixed base in Onshape. It's 100 mm across, with a rectangular opening for the servo and a hollow underside. The outside support wall is 30 mm tall. The slot isn't exactly in the middle because the servo shaft is offset from the centre of its body. I was still figuring out how the mounting ears and screws would hold everything in place.

![Fixed base with servo opening](images/2026-07-24-fixed-base-top.png)

![Hollow underside of the fixed base](images/2026-07-24-fixed-base-underneath.png)

**Total time spent: 1 hour**

# July 25, 2026: Designing the rotating shoulder mount

I worked on the smaller platform that will rotate above the fixed base. I measured the servo horn and made a test piece for its connection. I realised I'd been measuring some hole positions from their edges instead of their centres, which explained why they weren't lining up properly.

I made an upright wall for the shoulder servo and added triangular supports behind it. The wall has an opening for the servo body and two mounting holes. I wanted to keep the original fixed-base design and build on it, rather than keep changing the whole layout.

![Rotating platform and supported shoulder wall in Onshape](images/2026-07-25-shoulder-platform.png)

**Total time spent: 1.5 hours**

# July 26, 2026: Preparing the base parts for printing

I put the fixed base and rotating shoulder platform into the slicer. The fixed base is upside down for printing, with its flat top on the build plate and the hollow part facing up. I checked the orientation and infill, then sent the parts to print.

I was wondering whether the SG90 would be able to turn the platform with the other servos and arm pieces on it. I haven't tested the finished arm, so I still need to check that as more parts are added.

![Fixed base and shoulder platform arranged in the slicer](images/2026-07-26-slicer.png)

**Total time spent: 30 minutes**

# September 18, 2026: Making the single-arm horn gauge

There's a jump from July to September in these dated notes. In between, I got the base parts printed and started assembling them. Some holes needed adjusting, and some were too close to the servo body to fit a nut. The assembly was starting to look good, but those connections still needed work.

I worked on a fit gauge for the single-arm horn that will connect to the upper arm. I made a circular pocket joined to a tapered section in Onshape. One side of the taper ended up straighter than the other, so I adjusted it to make the sides match. After printing, the horn could fit into the outline, but it didn't sit evenly in the pocket.

![Circular and tapered horn pocket in Onshape](images/2026-09-18-horn-pocket.png)

**Total time spent: 45 minutes**

# September 19, 2026: Checking the horn fit

I tried making the pocket deeper because the horn wasn't sitting properly. Even at 3.3 mm deep, pressing the narrow end made it sink and tilt. I took the horn out and checked it on the table, where it stayed flat.

I took side photos to show the thicker connector and the thinner arm. Making the whole pocket deeper hadn't fixed the uneven support. I also tried sorting out the screws, but the ones I had weren't fitting the centre connection. That part still isn't resolved.

![Side view of the servo horn showing its thickness changes](images/horn-side-view.png)

**Total time spent: 35 minutes**

# September 20, 2026: Adding mounting holes to the gauge

I measured from the centre of the connector hole to two small holes along the horn. I got about 5.5 mm to the nearest one and 15.2 mm to the farthest one. I used those positions for the holes in the printed gauge and chose 2.8 mm clearance holes for the silver screws, based on holes I'd used before.

I also asked about significant figures and uncertainty because I'm learning them in school. Measuring the centre of a tiny hole made that feel more relevant. The caliper reading isn't the only thing that affects the measurement.

I sent the gauge to print and worked on the journal while waiting. I still need to check the fit and screw connection before saying this version works.

![Single-arm horn placed in the printed fit gauge](images/current-build.jpg)

**Total time spent: 40 minutes**


# October 15, 2026: Redesigning the base support

I came back to the base because I was worried about the SG90 supporting the platform and the rest of the arm. I looked at a few redesign ideas, but I don't have bearings, so I wanted to try something I could print. I also wanted to make more of the design decisions myself instead of following every step.

I added a circular wall underneath the rotating platform and a matching groove in the fixed base. The idea is for the wall to rest in the groove and share the weight, rather than leaving the platform supported only by the servo horn. The groove is 4 mm deep, and the wall has a 65 mm outer diameter and a 58 mm inner diameter.

At first, I gave the groove those same diameters. That left no clearance, which could make the printed parts bind. I worked out a test fit with a 65.6 mm outer groove diameter and a 57.4 mm inner diameter. That leaves 0.3 mm of space on each side, but it doesn't remove the friction underneath where the parts touch.

I also worked on a smaller fit test so I wouldn't need to reprint the whole base just to check the groove. The plan is to use a quarter-circle section instead of scaling everything down, because scaling would shrink the clearance too. I haven't confirmed the printed fit yet, and I'm still concerned about how much friction the SG90 will have to overcome.

![Redesigned base with a supporting skirt beneath the rotating platform](images/2026-10-15-base-redesign.png)

**Total time spent: 1 hour**

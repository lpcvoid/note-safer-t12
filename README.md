
I recently bought a KSGER T12 iron due to its good reviews. The PCB itself is already pretty good - beefy isolation slots, dual fused, and easily servicable, but I did two things additionally.

![PCB](https://i.imgur.com/pXvoC45.png)

# Adding a ground connection to the case

If using a connector with ground capabilities (which should be standard for metal cased and not double insulated devices such as this), the device grounds the tip for ESD safety. The case is not grounded though, so I recommend a small modification.

![Grounded case](https://i.imgur.com/BrnBP4y.png)

# Increase isolation distance between heatsink and trace

As title suggests, I cut away a small part of the heatsink for the mosfet, so there's a larger distance to the live trace. Here is the problem:

![Needs moar isloation](https://i.imgur.com/A4nDooj.png)

Removed the heatsink:

![Removed heatsink](https://i.imgur.com/Crraa4H.png)

I chose to cut three fins, that gave enough clearance.

![Cut heatsink](https://i.imgur.com/U50wk9A.png)

Resolder and screw back in place. You might also want to add thermal paste, that way both TO-220 packages won't get as hot. Afterwards, I think this is a extremly good iron that's very cheap, and if something craps out it's easy to replace.

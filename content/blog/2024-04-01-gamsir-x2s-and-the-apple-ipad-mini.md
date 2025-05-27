---
title: "Gamsir X2s and the Apple iPad Mini"
date: 2024-04-01T10:45:35-0400
draft: false
---
The [GameSir X2s](https://www.gamesir.hk/products/gamesir-x2s), recently released, boasts compatibility with iOS devices that support USB-C. Unfortunately, the controller does not expand far enough to accommodate devices larger than a phone.

However, the controller _can_ expand to a larger size. By forcing the controller out of its internal track it can be stretched to fit even the largest 12.9 inch iPad Pro. 

I wanted to use the GameSir with my iPad mini. I thought that with a bit of modification, I could greatly improve the clunky out-of-the-box experience. I designed and 3D printed a few parts that hide the exposed springs and lets the iPad fit flush and secure.

The end result looks like this:

{{< figure src="/images/blog/2024-04-01-gamsir-x2s-and-the-apple-ipad-mini/img-1254.jpeg" title="IMG_1254.jpeg" >}}

{{< figure src="/images/blog/2024-04-01-gamsir-x2s-and-the-apple-ipad-mini/img-1261.jpeg" title="IMG_1261.jpeg" >}}

## Warning

While this mod doesn't require physical harm to your GameSir X2s, it might end up being semi-permanent. In my case, I had to physically break the prototype 3D print to remove it from my GameSir X2s. The second 3D model, created for this post, should be easier to remove, but it might still require some effort. **Keep in mind that after this modification, the controller may no longer work with devices smaller than your Apple iPad mini.**

## 3D Modeling

For the design, I utilized [Shapr3D](https://www.shapr3d.com/). Although I chose Shapr3D initially for its aesthetics and ease of use, its subscription pricing does not make sense for my use case. Next time, I'll opt for [Autodesk Fusion 360](https://www.autodesk.com/products/fusion-360/personal), which offers a free license for personal use, despite being less intuitive than Shapr3D.

## Parts List

1x [Apple iPad mini (6th Generation)](https://www.amazon.com/Apple-iPad-Mini-6th-Generation/dp/B09G9JQBQH/)

1x [GameSir X2s](https://www.amazon.com/GameSir-Controller-Android-HarmonyOS-Genshin/dp/B0CRTMNQBL)

1x Custom X2s Frame

1x Custom X2s Backboard

4x [M4x10mm Flat Head Screws.](https://www.amazon.com/dp/B08P5MWGK6?psc=1&ref=ppx_yo2ov_dt_b_product_details) I used hex sockets. The maximum length of the screw should be 10mm.

4x [M4 Square Nuts.](https://www.amazon.com/dp/B07SDL3WJS?psc=1&ref=ppx_yo2ov_dt_b_product_details) These should be approximately 7mm x 7mm x 3.5mm.

1x [1mm Thick Self Adhesive Felt Sheet.](https://www.amazon.com/dp/B0C6DZRPXY?psc=1&ref=ppx_yo2ov_dt_b_product_details) Any color will do!

## 3D Printing

**You can download the required 3D models [here](https://github.com/timbueno/GameSirX2sMod/releases/download/v1.0/GameSir_X2s_iPad_mini_3d_models.zip).**

I have very limited experience with 3D printing, having only printed four items for this project. Therefore, I'm not an authority on the subject. The following is what worked for me.

I used Fused Deposition Modeling (FDM) with white ABS material and a completely solid infill. You may experiment with different infill densities and materials. Let me know what you like best!

All STL files for this project are in millimeters. You will likely need to specify that with the printer.

I utilized Xometry to print my models. Use my referral link [here](https://www.reddit.com/r/augmentedreality/comments/r53a77/how_can_i_embed_a_3d_model_and_ar_files_on_my/) and we'll both get a couple bucks off our next print. 

Another service for 3D printing is [Craftcloud](https://craftcloud3d.com/). Depending on your preferences, you may find CraftCloud is a cheaper option.

I think the models turned out pretty great!

{{< figure src="/images/blog/2024-04-01-gamsir-x2s-and-the-apple-ipad-mini/img-1227.jpeg" title="IMG_1227.jpeg" >}}

{{< figure src="/images/blog/2024-04-01-gamsir-x2s-and-the-apple-ipad-mini/img-1230.jpeg" title="IMG_1230.jpeg" >}}

## Assembly

Using the 3D printed backboard as a template, trace its outline onto the felted sheet. Cut the sheet slightly smaller than the outline and round the corners to match the backboard.

{{< figure src="/images/blog/2024-04-01-gamsir-x2s-and-the-apple-ipad-mini/img-1260.jpeg" title="IMG_1260.jpeg" >}}

Insert the square nuts, flat side up, into the slots beneath the holes in the 3D printed frame. You may find it helpful to cover the slots with a small piece of scotch tape to aid in this process.

{{< figure src="/images/blog/2024-04-01-gamsir-x2s-and-the-apple-ipad-mini/img-1239.jpeg" title="IMG_1239.jpeg" >}}

**Note: You may find that having two people makes the following easier.**

Expand the GameSir X2s controller and gently lift the rear purple casing while pulling to dislodge the two halves from one another.

Slide the frame onto the right half of the controller and insert the "tongue" of the frame into the left half to prevent flexing. Allow the two halves of the controller to come back together with the frame in place.

Align the 3D printed backboard with the holes in the frame, ensuring the nuts are lined up within the holes. Insert and tighten the M4 screws to secure the backboard to the frame. The countersunk holes should ensure the screws fit flush with the backboard.

{{< figure src="/images/blog/2024-04-01-gamsir-x2s-and-the-apple-ipad-mini/img-1242.jpeg" title="IMG_1242.jpeg" >}}

Peel and stick the felted sheet onto the backboard, ensuring alignment on all sides for a perfect fit.

{{< figure src="/images/blog/2024-04-01-gamsir-x2s-and-the-apple-ipad-mini/img-1247.jpeg" title="IMG_1247.jpeg" >}}

Using a craft knife, trim away the top and bottom two rubber "fingers" that secure the iPad into the controller. If not trimmed, these fingers may press the power and volume buttons on the iPad.

{{< figure src="/images/blog/2024-04-01-gamsir-x2s-and-the-apple-ipad-mini/img-1259.jpeg" title="IMG_1259.jpeg" >}}

Insert your iPad mini into the controller. The controller will have to expand slightly in order to fit. 

Happy gaming! Feel free to customize the 3D models to your liking. I'm sure the models could be easily modified for other device sizes. I'd love to see what the community comes up with!

Please send me a picture on [Mastodon](https://mastodon.social/@timbueno) if you end up modifying your GameSir X2s with my models!






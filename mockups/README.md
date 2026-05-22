# Mockups & Renders

Drop concept renders for the Foundry spaces in here, then add a matching
`<img>` for each one inside the `<template id="gallery-mockups">` block in
`index.html`. The lightbox carousel reads them in order.

Example:

```html
<template id="gallery-mockups">
  <img src="mockups/workshop-floor.jpg" alt="The Workshop — coworking floor" />
  <img src="mockups/core-racks.jpg"     alt="The Core — data centre" />
  <img src="mockups/studios-booth.jpg"  alt="The Studios — podcast booth" />
</template>
```

The `alt` text doubles as the caption shown in the lightbox.

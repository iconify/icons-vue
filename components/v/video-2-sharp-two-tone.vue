<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="e7ss9ccej"/><path class="en-r6acuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:video-2-sharp-two-tone" /></template>
<style>
.e7ss9ccej {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 5C17.5523 5 18 5.44772 18 6V8.38184L21.5527 6.60547C21.8626 6.45051 22.2306 6.46733 22.5254 6.64941C22.8202 6.83162 23 7.15343 23 7.5V16.5C23 16.8466 22.8202 17.1684 22.5254 17.3506C22.2306 17.5326 21.8626 17.5495 21.5527 17.3945L18 15.6182V18C18 18.5523 17.5523 19 17 19H2C1.44772 19 1 18.5523 1 18V6C1 5.44772 1.44772 5 2 5H17Z");
  stroke: none;
}

.en-r6acuh {
  d: path("M2 6L17 6L17 18L2 18ZM17 10L22 7.5L22 16.5L17 14");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

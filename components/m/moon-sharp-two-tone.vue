<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qz2ibpbaq"/><path class="wy4wumbry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:moon-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qz2ibpbaq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 12C22 17.3848 17.3848 22 12 22C6.6152 22 2 17.3848 2 12C2 6.6152 6.6152 2 12 2C12.8385 2 13.3047 2.9699 12.7809 3.6247C10.9814 5.874 11.1425 8.7837 13.1794 10.8206C15.2163 12.8575 18.126 13.0186 20.3753 11.2191C21.0301 10.6953 22 11.1615 22 12Z");
  stroke: none;
}

.wy4wumbry {
  d: path("M21 12C21 16.9706 16.9706 21 12 21C7.0294 21 3 16.9706 3 12C3 7.0294 7.0294 3 12 3C9.9618 5.5477 10.1652 9.2206 12.4723 11.5277C14.7794 13.8348 18.4523 14.0382 21 12Z");
}

</style>

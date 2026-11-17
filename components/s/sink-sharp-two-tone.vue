<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="cdx7nbvry"/><path class="s-9xc8bbu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sink-sharp-two-tone" /></template>
<style>
.cdx7nbvry {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 22C21 22.552 20.552 23 20 23H4C3.448 23 3 22.552 3 22V13H21V22Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s-9xc8bbu {
  d: path("M1 14H23M4 14V22H20V14M12 14V5C12 3.343 13.343 2 15 2C16.657 2 18 3.343 18 5V7M16 14V10H21M8 14V10H3");
}

</style>

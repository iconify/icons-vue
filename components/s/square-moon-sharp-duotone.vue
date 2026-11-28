<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lhggm9bsr"/><path class="sl5hze4cs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-moon-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lhggm9bsr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2H21C21.552 2 22 2.4477 22 3V21C22 21.5523 21.552 22 21 22H3C2.448 22 2 21.5523 2 21V3C2 2.4477 2.448 2 3 2Z");
  stroke: none;
}

.sl5hze4cs {
  d: path("M17 12C17 14.7614 14.761 17 12 17C9.239 17 7 14.7614 7 12C7 9.2386 9.239 7 12 7C10.868 8.4154 10.981 10.4559 12.262 11.7376C13.544 13.0193 15.585 13.1323 17 12Z");
}

</style>

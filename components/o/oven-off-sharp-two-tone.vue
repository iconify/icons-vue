<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jve8qk2lc"/><path class="nfr7zebzq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:oven-off-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jve8qk2lc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 21V22C21 22.552 20.552 23 20 23H4C3.448 23 3 22.552 3 22V3L21 21ZM4.743 1H20C20.552 1 21 1.448 21 2V17.257L4.743 1Z");
  stroke: none;
}

.nfr7zebzq {
  d: path("M20 20V22H4V4M4 10H10M8 14H14M1.707 1.707L22.293 22.293");
}

</style>

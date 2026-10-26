<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mkahplxkq"/><path class="abui5slpu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mails-sharp-two-tone" /></template>
<style>
.abui5slpu {
  d: path("M2 14L2 4L16 4M6 8L22 8L22 20L6 20ZM6 11L14 14.4435L22 11");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mkahplxkq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 7L22 7C22.5523 7 23 7.4477 23 8L23 20C23 20.5523 22.5523 21 22 21L6 21C5.4477 21 5 20.5523 5 20L5 8C5 7.4477 5.4477 7 6 7Z");
  stroke: none;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="nsxhdcxdq"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:play-off-sharp-duotone" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nsxhdcxdq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15.1211 15.1211L6.5547 20.8321C6.3904 20.9416 6.1974 21 6 21C5.4477 21 5 20.5523 5 20L5 5ZM7.365 3.7082L18.5547 11.1679C18.8329 11.3534 19 11.6656 19 12C19 12.3344 18.8329 12.6466 18.5547 12.8321L17.3152 13.6584Z");
  stroke: none;
}

</style>

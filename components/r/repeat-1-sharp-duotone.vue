<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kvt67ihpg"/><path class="yv4c-x_5c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:repeat-1-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kvt67ihpg {
  stroke-opacity: 0.4;
  d: path("M3 18L21 18L21 5L15.5 5M6.2929 14.7071L3 18L6.2929 21.2929");
}

.yv4c-x_5c {
  d: path("M10.5547 4.2968L12.5 3L12.5 10M3 12L3 5L8 5");
}

</style>

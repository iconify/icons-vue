<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="daaep74_v"/><path class="e1ij25anb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-pause-corner-duocolor-sharp" /></template>
<style>
.daaep74_v {
  stroke-opacity: 0.4;
  d: path("M15 13v8m4-8v8");
}

.e1ij25anb {
  d: path("M5 7a4 4 0 1 0 8 0a4 4 0 0 0-8 0M3 21a6 6 0 0 1 6-6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

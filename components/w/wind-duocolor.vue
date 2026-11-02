<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x3ev36gwm"/><path class="roo9lfb1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wind-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.roo9lfb1y {
  d: path("M3 7h8a2 2 0 1 0 0-4M3 17h11a2 2 0 1 1 0 4");
}

.x3ev36gwm {
  stroke-opacity: 0.4;
  d: path("M3 12h15a3 3 0 0 0 0-6");
}

</style>

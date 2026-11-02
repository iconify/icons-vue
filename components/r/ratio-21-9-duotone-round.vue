<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cowy1jbzo"/><path class="lw45_5d3j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ratio-21-9-duotone-round" /></template>
<style>
.cowy1jbzo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 8h10a4 4 0 0 1 0 8H7a4 4 0 0 1 0-8");
}

.ft5dv1b6b {
  fill: none;
}

.lw45_5d3j {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12a4 4 0 0 1 4-4h10a4 4 0 1 1 0 8H7a4 4 0 0 1-4-4");
}

</style>

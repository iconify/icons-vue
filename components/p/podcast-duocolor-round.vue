<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b_yr8yb8d"/><path class="rar5j9b-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:podcast-duocolor-round" /></template>
<style>
.b_yr8yb8d {
  stroke-opacity: 0.4;
  d: path("M8 15a5 5 0 1 1 8 0M3 12a9 9 0 0 1 18 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rar5j9b-h {
  d: path("M11 12a1 1 0 1 0 2 0a1 1 0 0 0-2 0m1 1v8");
}

</style>

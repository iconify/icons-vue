<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="srb0z50wz"/><path class="sikk-ubak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:save-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.sikk-ubak {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21H7a4 4 0 0 1-4-4V7a4 4 0 0 1 4-4h8c1.28 0 2.36.36 3 1l2 2c.64.64 1 1.72 1 3v8a4 4 0 0 1-4 4zm-5 0v-3a4 4 0 0 1 4-4h2a4 4 0 0 1 4 4v3M9 7h6");
}

.srb0z50wz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 21H7a4 4 0 0 1-4-4V7a4 4 0 0 1 4-4h8c1.041 0 2.236.237 3 1l2 2c.763.764 1 1.959 1 3v8a4 4 0 0 1-4 4");
}

</style>

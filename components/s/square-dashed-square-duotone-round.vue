<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cr97ugmjt"/><path class="cozg1xwmy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-duotone-round" /></template>
<style>
.cozg1xwmy {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6a3 3 0 0 1 3-3m12 0a3 3 0 0 1 3 3m0 12a3 3 0 0 1-3 3M10 3h4m7 7v4M3 14a4 4 0 0 1 4-4h3a4 4 0 0 1 4 4v3a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Z");
}

.cr97ugmjt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 9h3a5 5 0 0 1 5 5v3a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5v-3a5 5 0 0 1 5-5");
}

.ft5dv1b6b {
  fill: none;
}

</style>

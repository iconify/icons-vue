<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xkd818b9i"/><path class="wy4f2f08l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-top-right-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.wy4f2f08l {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6a3 3 0 0 1 3-3m15 15a3 3 0 0 1-3 3M6 21a3 3 0 0 1-3-3m11 3h-4m-7-7v-4m7-3a4 4 0 0 1 4-4h3a4 4 0 0 1 4 4v3a4 4 0 0 1-4 4h-3a4 4 0 0 1-4-4Z");
}

.xkd818b9i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M14 2h3a5 5 0 0 1 5 5v3a5 5 0 0 1-5 5h-3a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5");
}

</style>

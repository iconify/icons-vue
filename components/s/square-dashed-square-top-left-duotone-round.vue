<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g54u8abcq"/><path class="jc2cfgb6b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-top-left-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g54u8abcq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 2h3a5 5 0 0 1 5 5v3a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5");
}

.jc2cfgb6b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 3a3 3 0 0 1 3 3m0 12a3 3 0 0 1-3 3M6 21a3 3 0 0 1-3-3m18-8v4m-7 7h-4M3 7a4 4 0 0 1 4-4h3a4 4 0 0 1 4 4v3a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Z");
}

</style>

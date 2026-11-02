<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p810y3l_l"/><path class="t-3azepph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:traffic-light-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.p810y3l_l {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 2h2a5 5 0 0 1 5 5v10a5 5 0 0 1-5 5h-2a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5");
}

.t-3azepph {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 7a4 4 0 0 1 4-4h2a4 4 0 0 1 4 4v10a4 4 0 0 1-4 4h-2a4 4 0 0 1-4-4Zm4 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m0 5a1 1 0 1 0 2 0a1 1 0 0 0-2 0m0 5a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>

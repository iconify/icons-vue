<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u8_q5ybwc"/><path class="jj8_o7bzh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wine-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jj8_o7bzh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 3h6c1.5 3.5 2 5.5 2 7a5 5 0 0 1-10 0c0-1.5.5-3.5 2-7m3 12v6m-4 0h8M7 10h10");
}

.u8_q5ybwc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 9h10a1 1 0 0 1 1 1a5.9 5.9 0 0 1-.472 2.336a6 6 0 0 1-1.285 1.907A5.98 5.98 0 0 1 12 16a5.97 5.97 0 0 1-4.243-1.757a6 6 0 0 1-1.285-1.907A5.9 5.9 0 0 1 6 10a1 1 0 0 1 1-1");
}

</style>

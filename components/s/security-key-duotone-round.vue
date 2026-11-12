<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ytjfw9b_b"/><path class="u32538w5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:security-key-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.u32538w5n {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 11a4 4 0 0 1 4-4h4a4 4 0 0 1 4 4v2a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Zm6 0v2m12-1h-2m-4-3h5a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-5");
}

.ytjfw9b_b {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 6h4a5 5 0 0 1 5 5v2a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5v-2a5 5 0 0 1 5-5");
}

</style>

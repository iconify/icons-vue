<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kziqlwbeq"/><path class="xafi2hben"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:venus-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kziqlwbeq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6.472 5.664a6.001 6.001 0 1 1 11.055 4.674A6.001 6.001 0 0 1 6.472 5.664");
}

.xafi2hben {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 8a5 5 0 1 0 10 0A5 5 0 0 0 7 8m5 5v8m-3-4h6");
}

</style>

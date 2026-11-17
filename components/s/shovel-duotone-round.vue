<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w15dwkbga"/><path class="nyf_if1vp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shovel-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nyf_if1vp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m11 13l2 2a1.414 1.414 0 0 1 0 2c-.64.64-1.36 1-2 1H9a3 3 0 0 1-3-3v-2c0-.64.36-1.36 1-2a1.414 1.414 0 0 1 2 0zm0 0l6-6m-2-2l4 4");
}

.w15dwkbga {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m9 11l4 4a1.415 1.415 0 0 1 0 2c-.521.52-1.237 1-2 1H9a3 3 0 0 1-3-3v-2c0-.763.48-1.479 1-2a1.415 1.415 0 0 1 2 0");
}

</style>

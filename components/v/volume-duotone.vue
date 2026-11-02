<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z742pybpy"/><path class="sy3ij1b_i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.sy3ij1b_i {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 6v12c0 .738-.631 1.369-1 1l-2-2c-.64-.64-1.36-1-2-1H5a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2h1c.64 0 1.36-.36 2-1l2-2c.369-.369 1 .262 1 1");
}

.z742pybpy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 18c0 .738-.631 1.369-1 1l-2-2c-.521-.52-1.237-1-2-1H5a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2h1c.763 0 1.479-.48 2-1l2-2c.369-.369 1 .262 1 1Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pbmm4dn8y"/><path class="q3i4wbcok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:money-bag-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pbmm4dn8y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m13 8l5 5c.763.764 1 1.959 1 3v2a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3v-2c0-1.041.237-2.236 1-3l5-5l-3-5h8Z");
}

.q3i4wbcok {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m13 8l5 5c.64.64 1 1.72 1 3v2a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3v-2c0-1.28.36-2.36 1-3l5-5l-3-5h8zm-3 0h4");
}

</style>

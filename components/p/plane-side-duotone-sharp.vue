<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qiuwl7bmg"/><path class="oiladab4b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-side-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.oiladab4b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5h2l3 5h13v4h-6l-5 5H8l2-5H5z");
}

.qiuwl7bmg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 5h2l3 5h13v4h-6l-5 5H8l2-5H5Z");
}

</style>

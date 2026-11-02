<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u4xi4bcet"/><path class="d-waackhr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:navigation-duotone-round" /></template>
<style>
.d-waackhr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 6l6 2c1.107.369.476 2.262-1 3l-2 1a6.7 6.7 0 0 0-3 3l-1 2c-.738 1.476-2.631 2.107-3 1L4 6c-.412-1.236.764-2.412 2-2z");
}

.ft5dv1b6b {
  fill: none;
}

.u4xi4bcet {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 8c1.107.369.476 2.262-1 3l-2 1a6.7 6.7 0 0 0-3 3l-1 2c-.738 1.476-2.631 2.107-3 1L4 6a1.58 1.58 0 0 1 2-2Z");
}

</style>

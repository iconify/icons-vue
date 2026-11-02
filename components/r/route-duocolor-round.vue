<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zx9_r_5jc"/><path class="uzcl_s0kh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:route-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uzcl_s0kh {
  d: path("M4 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0M16 6H9a3 3 0 0 0 0 6h6a3 3 0 0 1 0 6H8");
}

.zx9_r_5jc {
  stroke-opacity: 0.4;
  d: path("M16 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>

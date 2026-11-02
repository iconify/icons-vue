<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p_8s37hao"/><path class="ek06zebyj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-duocolor" /></template>
<style>
.ek06zebyj {
  d: path("M3 6V5a2 2 0 0 1 2-2h1m12 0h1a2 2 0 0 1 2 2v1m0 12v1a2 2 0 0 1-2 2h-1M10 3h4m7 7v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p_8s37hao {
  stroke-opacity: 0.4;
  d: path("M3 12a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

</style>

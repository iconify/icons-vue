<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="izs2jcbci"/><path class="w-08odbih"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-vertical-3-duocolor" /></template>
<style>
.izs2jcbci {
  stroke-opacity: 0.4;
  d: path("M4 10h4m2 6h4m2-9h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w-08odbih {
  d: path("M6 3v7m0 4v7m6-18v13m0 4v1m6-18v4m0 4v10");
}

</style>

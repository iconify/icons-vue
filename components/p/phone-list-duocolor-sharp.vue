<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qf54pxbub"/><path class="ricnuhbyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-list-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qf54pxbub {
  stroke-opacity: 0.4;
  d: path("M15 3h6m-6 3h6m-6 3h6");
}

.ricnuhbyg {
  d: path("M3 5V3h6l2 5l-3 3l5 5l3-3l5 2v6h-2C10.163 21 3 13.837 3 5");
}

</style>

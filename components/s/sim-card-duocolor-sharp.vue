<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q8-pf9_0v"/><path class="dufnb_byj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sim-card-duocolor-sharp" /></template>
<style>
.dufnb_byj {
  d: path("M5 3h10l4 4v14H5z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q8-pf9_0v {
  stroke-opacity: 0.4;
  d: path("M9 9h6v8H9Zm0 4h6");
}

</style>

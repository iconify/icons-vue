<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ooyw8-y8g"/><path class="i7bdhbb4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-bag-duocolor-sharp" /></template>
<style>
.i7bdhbb4s {
  d: path("M5 6h14v15H5Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ooyw8-y8g {
  stroke-opacity: 0.4;
  d: path("M9 6a3 3 0 0 1 6 0");
}

</style>

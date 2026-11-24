<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a0wzdrbnn"/><path class="itf1p5nbq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:windmill-duocolor-sharp" /></template>
<style>
.a0wzdrbnn {
  stroke-opacity: 0.4;
  d: path("M10 8a2 2 0 1 0 4 0a2 2 0 0 0-4 0m.586-1.414L7 3m6.414 3.586L17 3m-3.586 6.414L17 13m-6.414-3.586L7 13");
}

.itf1p5nbq {
  d: path("m12 15l4 2l1 4H7l1-4zm-9 6h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

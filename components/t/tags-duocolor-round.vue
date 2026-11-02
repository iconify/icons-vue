<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rn_bmmbhp"/><path class="qedvzww7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tags-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qedvzww7q {
  d: path("M6 6h1c1.28 0 2.36.36 3 1l2 2a4.243 4.243 0 0 1-6 6l-2-2c-.64-.64-1-1.72-1-3V9a3 3 0 0 1 3-3m1 4h.01");
}

.rn_bmmbhp {
  stroke-opacity: 0.4;
  d: path("m15 6l3 3a4.243 4.243 0 0 1 0 6l-3 3");
}

</style>

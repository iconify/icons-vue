<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fee-8zjmr"/><path class="vbtgc8bua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pill-duocolor-round" /></template>
<style>
.fee-8zjmr {
  stroke-opacity: 0.4;
  d: path("m9 9l-4 4a4.243 4.243 0 0 0 6 6l4-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vbtgc8bua {
  d: path("m9 9l4-4a4.243 4.243 0 0 1 6 6l-4 4M9 9l6 6");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r1xs12btp"/><path class="ukw8xsckr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tags-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r1xs12btp {
  stroke-opacity: 0.4;
  d: path("m15 6l6 6l-6 6");
}

.ukw8xsckr {
  d: path("M6 6h3l6 6l-6 6l-6-6V6zm1 4h.01");
}

</style>

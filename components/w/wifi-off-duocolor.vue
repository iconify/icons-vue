<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p52u7fomt"/><path class="kus8t0b2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wifi-off-duocolor" /></template>
<style>
.kus8t0b2k {
  d: path("M9 16a3.606 3.606 0 0 1 5-1m-8-2a7.8 7.8 0 0 1 4-2m-7-1a12 12 0 0 1 3-3m9 4a7.8 7.8 0 0 1 4 3m-9-8a12.04 12.04 0 0 1 11 4m-9 9h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p52u7fomt {
  stroke-opacity: 0.4;
  d: path("m2 3l19 19");
}

</style>

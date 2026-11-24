<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qbt2u0boe"/><path class="l4djeccec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-minus-duocolor" /></template>
<style>
.l4djeccec {
  d: path("M6 20v-3l9-9a1.414 1.414 0 0 1 2 0l1 1a1.414 1.414 0 0 1 0 2l-9 9zm8-11l3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qbt2u0boe {
  stroke-opacity: 0.4;
  d: path("M4 7h6");
}

</style>

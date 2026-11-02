<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qp-r10b4n"/><path class="ed868obsq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:strikethrough-duocolor-round" /></template>
<style>
.ed868obsq {
  d: path("M16 6a5 5 0 1 0-8 6m8 0a5 5 0 0 1-8 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qp-r10b4n {
  stroke-opacity: 0.4;
  d: path("M4 12h16");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qpemshbvq"/><path class="gcy62xbec"/><path class="qqsn8sb7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:online-status-outline-regular" /></template>
<style>
.gcy62xbec {
  d: path("M6.5 16a4.5 4.5 0 0 1 9 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qpemshbvq {
  d: path("M8 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.qqsn8sb7q {
  d: path("M17 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>

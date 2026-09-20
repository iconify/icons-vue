<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r21jxhxfq"/><path class="o19v3ublc"/><path class="kx2zklb7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:plant-cell-outline-regular" /></template>
<style>
.kx2zklb7n {
  d: path("M13 9h5v6h-5Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o19v3ublc {
  d: path("M5 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.r21jxhxfq {
  d: path("M3 5h18v14H3Z");
}

</style>

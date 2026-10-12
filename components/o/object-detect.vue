<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gd_1a3mcf"/><path class="toehbab5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:object-detect" /></template>
<style>
.gd_1a3mcf {
  d: path("M3.25 7.5V5.75a2.5 2.5 0 0 1 2.5-2.5H7.5m9 0h1.75a2.5 2.5 0 0 1 2.5 2.5V7.5m0 9v1.75a2.5 2.5 0 0 1-2.5 2.5H16.5m-9 0H5.75a2.5 2.5 0 0 1-2.5-2.5V16.5m9.44-9.6l3.37 1.95q.69.4.69 1.2v3.9q0 .8-.69 1.2l-3.37 1.95q-.69.4-1.38 0l-3.37-1.95q-.69-.4-.69-1.2v-3.9q0-.8.69-1.2l3.37-1.95q.69-.4 1.38 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.toehbab5l {
  d: path("M7.6 9.45L12 12l4.4-2.55M12 12v5.1");
}

</style>

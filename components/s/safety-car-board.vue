<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gzwzpibrh"/><path class="kvffg2edq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:safety-car-board" /></template>
<style>
.gzwzpibrh {
  d: path("M2.5 3h19v13h-19ZM12 16v5.5");
}

.kvffg2edq {
  d: path("M5.5 12v-2L8 9.5L9.75 7h4.5L16 9.5l2.5.5v2H17a1.75 1.75 0 0 0-3.5 0h-3A1.75 1.75 0 0 0 7 12Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

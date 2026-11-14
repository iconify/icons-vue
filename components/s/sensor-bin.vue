<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbqy5-nwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sensor-bin" /></template>
<style>
.qbqy5-nwt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 3h13A1.5 1.5 0 0 1 20 4.5A1.5 1.5 0 0 1 18.5 6h-13A1.5 1.5 0 0 1 4 4.5A1.5 1.5 0 0 1 5.5 3m0 3L7 21h10l1.5-15M12 9.5h.01m-5.76 4h11.5");
}

</style>

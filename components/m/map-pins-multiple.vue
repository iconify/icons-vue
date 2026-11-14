<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vx1y5p1-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:map-pins-multiple" /></template>
<style>
.vx1y5p1-i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5c-2-2-4.5-4.75-4.5-7.75a4.5 4.5 0 0 1 9 0c0 3-2.5 5.75-4.5 7.75M5 9.25C3.75 8 2.5 6.75 2.5 5a2.5 2.5 0 0 1 5 0c0 1.75-1.25 3-2.5 4.25m13.5 1.5c-1.25-1.25-3-2.75-3-5.25a3 3 0 0 1 6 0c0 2.5-1.75 4-3 5.25m-6.5 3h.01");
}

</style>

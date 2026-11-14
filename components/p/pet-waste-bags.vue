<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ofyd5l4gy"/><path class="fgc-f2btb"/><path class="u7lguny_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pet-waste-bags" /></template>
<style>
.fgc-f2btb {
  fill: currentColor;
  d: path("M10.25 16.25a1.75 1.25 0 1 0 3.5 0a1.75 1.25 0 1 0-3.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ofyd5l4gy {
  d: path("M8 2.5h8A3.5 3.5 0 0 1 19.5 6v.5A3.5 3.5 0 0 1 16 10H8a3.5 3.5 0 0 1-3.5-3.5V6A3.5 3.5 0 0 1 8 2.5M7 10v10.5l2.5 1l2.5-1l2.5 1l2.5-1V10");
}

.u7lguny_r {
  d: path("M10 13.5h.01M12 13h.01m1.99.5h.01");
}

</style>

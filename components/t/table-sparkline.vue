<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eff7vbrbp"/><path class="npt6qybnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:table-sparkline" /></template>
<style>
.eff7vbrbp {
  d: path("M6.875 2.5h10.25A4.375 4.375 0 0 1 21.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 17.125V6.875A4.375 4.375 0 0 1 6.875 2.5M2.5 9h19m-19 6h19m-16-9.25h4M5.5 12h4m-4 6.25h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.npt6qybnt {
  d: path("m12.5 6.75l2-2l1.5 1.5l2.5-1.5m-6 8l2-1.25l1.5 1.25L18.5 11m-6 7l2 1.25l1.5-1.5L18.5 19");
}

</style>

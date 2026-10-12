<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="itr829b-o"/><path class="a7xbknbyy"/><path class="xk-t4kr0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:soil-sensor-sharp" /></template>
<style>
.a7xbknbyy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6.75h.01");
}

.itr829b-o {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3.5h7V10h-7z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xk-t4kr0y {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 10v6m3-6v6m4.25-11.5l2.551 2.25L17.75 9m2-6a5.5 5.5 0 0 1 0 7.5m-17 5.5h18.5v5.25H2.75zm7.75 0v3m3-3v3");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="xz2plnk4c"/><path class="kj2txzbaz"/><path class="etxt20ith"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:month-view" /></template>
<style>
.etxt20ith {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.38 17.63h.01");
}

.kj2txzbaz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 8.25h17.5m-8.75 0v12.5M3.25 14.5h17.5");
}

.xz2plnk4c {
  width: 17.5px;
  height: 17.5px;
  x: 3.25px;
  y: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

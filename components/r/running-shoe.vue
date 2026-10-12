<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gbx8mtb1b"/><rect class="qb0iet71u"/><path class="o7h5t5b2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:running-shoe" /></template>
<style>
.gbx8mtb1b {
  d: path("M2.75 14.25V6.5A1.25 1.25 0 0 1 4 5.25h1.75a3 3 0 0 0 3 2.75H10l2.25-2.25l7.1 4.75a4.5 4.5 0 0 1 1.9 3.75Zm10-6L11.5 10m3.5-.25l-1.25 1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o7h5t5b2k {
  d: path("M7 18.88h2m2 0h2m2 0h2");
}

.qb0iet71u {
  width: 18.5px;
  height: 4.75px;
  x: 2.75px;
  y: 16.5px;
  rx: 1.5px;
}

</style>

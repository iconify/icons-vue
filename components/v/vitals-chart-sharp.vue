<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ohxdrbbbi"/><path class="xo46-mbjv"/><path class="eqw_z4b0h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vitals-chart-sharp" /></template>
<style>
.eqw_z4b0h {
  d: path("M8.25 13h1.5L11 10.5l2 5l2-7l1.25 4.5h1.25");
}

.ohxdrbbbi {
  d: path("M3.75 2.75h16.5v18.5H3.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xo46-mbjv {
  d: path("M6.75 6.25V18h10.5");
}

</style>

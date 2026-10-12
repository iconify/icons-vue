<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="h5_kxlgjn"/><path class="ztrnz5yjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:property-valuation-sharp" /></template>
<style>
.h5_kxlgjn {
  d: path("M2.75 17V8.15l.77-.64l4.96-4.12l.77-.64l.77.64l4.96 4.12l.77.64V18h-13z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ztrnz5yjf {
  d: path("m11 21l3.5-3.75l2.5 2l4.25-5m-3.5 0h3.5v3.5");
}

</style>

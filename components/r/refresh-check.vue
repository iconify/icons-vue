<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sxtlwx92v"/><path class="el34zpb9u"/><path class="q3rszkvjm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:refresh-check" /></template>
<style>
.el34zpb9u {
  d: path("m15.5 9l3 3l3-3m-3.871 6.25A6.5 6.5 0 0 1 5.5 12");
}

.q3rszkvjm {
  d: path("m2.5 15l3-3l3 3m1.5-3l1.5 1.5L14 11");
}

.sxtlwx92v {
  d: path("M6.371 8.75A6.5 6.5 0 0 1 18.5 12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

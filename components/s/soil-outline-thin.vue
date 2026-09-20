<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k187sabpz"/><path class="ils7yp4cg"/><path class="oqfv9rb9x"/><path class="elo_ccj2r"/><path class="xh1xf-b_h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:soil-outline-thin" /></template>
<style>
.elo_ccj2r {
  d: path("M9 4v7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ils7yp4cg {
  d: path("M2 16h20");
}

.k187sabpz {
  d: path("M2 11h20");
}

.oqfv9rb9x {
  d: path("M2 21h20");
}

.xh1xf-b_h {
  d: path("M10 9c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
}

</style>

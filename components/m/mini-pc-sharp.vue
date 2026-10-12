<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="r4um8ibid"/><path class="t8g1vpp5m"/><path class="vf68qibdo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mini-pc-sharp" /></template>
<style>
.r4um8ibid {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9.25h18.5v7.5H2.75zM6.25 13h5");
}

.t8g1vpp5m {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 13h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vf68qibdo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 19.75h10.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e9e3_hbwn"/><rect class="ngrjfrbtj"/><path class="cvenlqlru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:travel-bag" /></template>
<style>
.cvenlqlru {
  d: path("M7.25 9.5v10m9.5-10v10m-7.25-7h5");
}

.e9e3_hbwn {
  d: path("M8.5 9c0-4.5 7-4.5 7 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ngrjfrbtj {
  width: 18.5px;
  height: 11px;
  x: 2.75px;
  y: 9px;
  rx: 5px;
}

</style>

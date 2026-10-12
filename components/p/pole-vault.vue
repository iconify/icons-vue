<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wch29_fzp"/><circle class="tsd9o8qdy"/><path class="a6hmy3b4l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pole-vault" /></template>
<style>
.a6hmy3b4l {
  d: path("M10.5 10v11.25m5-11.25v11.25M10.5 10h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tsd9o8qdy {
  cx: 19.75px;
  cy: 8.75px;
  r: 1.25px;
}

.wch29_fzp {
  d: path("M3.25 21.25c1-5 2.25-9 4.25-12.25C10 5.25 16 4.75 18.6 7.9");
}

</style>

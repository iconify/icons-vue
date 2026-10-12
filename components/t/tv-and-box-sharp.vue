<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="g-rtc5-ic"/><path class="s7hdf8bld"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tv-and-box-sharp" /></template>
<style>
.g-rtc5-ic {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v11.5H2.75zm3.5 14.5h11.5v4H6.25z");
}

.s7hdf8bld {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.75 19.25h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

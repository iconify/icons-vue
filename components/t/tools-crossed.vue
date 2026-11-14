<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vi-y5jnwu"/><path class="apq5zrb-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tools-crossed" /></template>
<style>
.apq5zrb-x {
  d: path("M15.5 3.75V7A1.5 1.5 0 0 0 17 8.5h3.25M4.5 19.5L12 12m.707.707za2.5 2.5 0 0 1 3.536 0l2.475 2.475a2.5 2.5 0 0 1 0 3.536a2.5 2.5 0 0 1-3.536 0l-2.475-2.475a2.5 2.5 0 0 1 0-3.536m0 0l-6.01-6.01m-.884.884l1.768-1.768");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vi-y5jnwu {
  d: path("M20.25 8.5a4.75 4.75 0 1 1-4.75-4.75");
}

</style>

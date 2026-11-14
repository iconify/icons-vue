<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t_wx_ib7e"/><path class="z03i8nbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:product-price-book" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t_wx_ib7e {
  d: path("M21 12.567V4.5q-6-.75-9 1.5q-3-2.25-9-1.5v14q5.868-.734 8.867 1.402M12 6v7.7");
}

.z03i8nbzn {
  d: path("M15.75 14.25h2.379a1.5 1.5 0 0 1 1.06.439l1.75 1.75a1.5 1.5 0 0 1 0 2.122l-2.378 2.378a1.5 1.5 0 0 1-2.122 0l-1.75-1.75a1.5 1.5 0 0 1-.439-1.06V15.75a1.5 1.5 0 0 1 1.5-1.5");
}

</style>

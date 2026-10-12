<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj-zdc0nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trousers" /></template>
<style>
.qj-zdc0nj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2.75h10q1.25 0 1.38 1.24l1.74 16.02q.13 1.24-1.12 1.24h-3q-1.25 0-1.43-1.24l-1.14-8.02q-.18-1.24-1.43-1.24t-1.43 1.24l-1.14 8.02Q9.25 21.25 8 21.25H5q-1.25 0-1.12-1.24L5.62 3.99Q5.75 2.75 7 2.75M5.75 6.5h12.5M12 6.5v2");
}

</style>

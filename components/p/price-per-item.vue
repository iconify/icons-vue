<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gl3vwq4ok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:price-per-item" /></template>
<style>
.gl3vwq4ok {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3.5H8A3.5 3.5 0 0 1 11.5 7v10A3.5 3.5 0 0 1 8 20.5H6.5A3.5 3.5 0 0 1 3 17V7a3.5 3.5 0 0 1 3.5-3.5M3 6.5h8.5M3 17.5h8.5m0-9l6 3m-2.561 2.561l1.5-1.5a1.5 1.5 0 0 1 2.122 0l1.5 1.5a1.5 1.5 0 0 1 .439 1.06V19a1.5 1.5 0 0 1-1.5 1.5h-3a1.5 1.5 0 0 1-1.5-1.5v-3.879a1.5 1.5 0 0 1 .439-1.06M17.5 15.25h.01");
}

</style>

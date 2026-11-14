<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6yf2_b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tick-bite" /></template>
<style>
.u6yf2_b4l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.5c3.5 1.5 5 5 5 8c0 3.25-2.25 5.5-5 5.5s-5-2.25-5-5.5c0-3 1.5-6.5 5-8Zm-1.25-3h2.5v2.75h-2.5Zm.75 0l-.25-1.75M12.5 4.5l.25-1.75M8 11L4.75 8.5m2.5 5l-3.75-1M7 16l-3.5 1m4.25 1.5l-3 2.5M16 11l3.25-2.5m-2.5 5l3.75-1M17 16l3.5 1m-4.25 1.5l3 2.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kee32d_ru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pull-buoy" /></template>
<style>
.kee32d_ru {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 2.5h6.5A3.75 3.75 0 0 1 19 6.25A3.75 3.75 0 0 1 15.25 10h-6.5A3.75 3.75 0 0 1 5 6.25A3.75 3.75 0 0 1 8.75 2.5m0 11.5h6.5A3.75 3.75 0 0 1 19 17.75a3.75 3.75 0 0 1-3.75 3.75h-6.5A3.75 3.75 0 0 1 5 17.75A3.75 3.75 0 0 1 8.75 14m1.75-4v4m3-4v4");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syxau8g6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:travel-allowance" /></template>
<style>
.syxau8g6b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21.5 9c0-.75-.75-1.25-1.5-1.25h-2.5L14.5 3h-1.75l1.5 4.75H11L9.75 6H8.5l.75 3l-.75 3h1.25L11 10.25h3.25L12.75 15h1.75l3-4.75H20c.75 0 1.5-.5 1.5-1.25m-13 .25C6 9.5 5 11 5.25 13M2 16.75a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m3.5-1.25V18");
}

</style>

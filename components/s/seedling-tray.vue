<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isg2grffv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seedling-tray" /></template>
<style>
.isg2grffv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.55 13.25h16.9q.8 0 .65.79l-1.2 6.42q-.15.79-.95.79H5.05q-.8 0-.95-.79l-1.2-6.42q-.15-.79.65-.79m4.95 0v8m7-8v8m-10-8V10m6.5 3.25V9m6.5 4.25V10m-13 0c0-1.75 1.1-2.75 3-2.75C8.5 9 7.4 10 5.5 10M12 9c0-2 1.25-3.25 3.5-3.25c0 2-1.25 3.25-3.5 3.25m0 0c0-2-1.25-3.25-3.5-3.25C8.5 7.75 9.75 9 12 9m6.5 1c0-1.75-1.1-2.75-3-2.75c0 1.75 1.1 2.75 3 2.75");
}

</style>

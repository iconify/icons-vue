<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgkr1acwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rescue-buoy" /></template>
<style>
.bgkr1acwo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 12a7 7 0 1 0 14 0a7 7 0 1 0-14 0m4.25 0a2.75 2.75 0 1 1 5.5 0a2.75 2.75 0 1 1-5.5 0m4.69 1.94l3.01 3.01m-6.89-3.01l-3.01 3.01m3.01-6.89L7.05 7.05m6.89 3.01l3.01-3.01");
}

</style>

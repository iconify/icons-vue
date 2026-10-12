<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzbwyofcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wastebasket" /></template>
<style>
.nzbwyofcj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 7.25a3.25 3.25 0 0 1 6.5 0Zm-4.5 0h15.5l-1.5 12.25a2 2 0 0 1-2 1.75h-8.5a2 2 0 0 1-2-1.75Zm1 3.25h13.5");
}

</style>

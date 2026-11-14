<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2z-dqb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:medal-ribbon-sport" /></template>
<style>
.y2z-dqb8t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 15.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0ZM6.5 3l4 7.25m7-7.25l-4 7.25M6.5 3h11");
}

</style>

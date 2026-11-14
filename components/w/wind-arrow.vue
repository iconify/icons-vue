<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrurj9xvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wind-arrow" /></template>
<style>
.hrurj9xvl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7.5h10A2.5 2.5 0 1 0 11 5m-7.5 7h17M18 9.5l2.5 2.5l-2.5 2.5m-14.5 2h11A2.5 2.5 0 1 1 12 19");
}

</style>

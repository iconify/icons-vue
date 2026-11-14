<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ybq7-gbzs"/><path class="y7eyo7b3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:route-multi-stop" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y7eyo7b3k {
  fill: currentColor;
  d: path("M17.5 19.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ybq7-gbzs {
  d: path("M2 19.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm5 0h7.7m4.8-4.8V7M17 4.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

</style>

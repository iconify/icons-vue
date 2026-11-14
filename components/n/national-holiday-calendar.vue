<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jdg0se-cj"/><path class="i4ah8ub0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:national-holiday-calendar" /></template>
<style>
.i4ah8ub0m {
  d: path("M15.5 21.5v-7H21l-1.75 2.25L21 19h-5.5");
}

.jdg0se-cj {
  d: path("M12.7 21H3V4h18v7.7M8 2.5V6m8-3.5V6M3 9h18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

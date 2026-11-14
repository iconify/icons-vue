<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jogakovpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:skills-matrix" /></template>
<style>
.jogakovpd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 4.25a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 1 1 0-2.5V5.5M12 4.25a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 1 1 0-2.5V5.5m6.5-1.25a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 1 1 0-2.5V5.5m-13 5.25a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 1 1 0-2.5V12m6.5-1.25a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 1 1 0-2.5V12m-6.5 5.25a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 1 1 0-2.5v1.25M16.75 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm-6.5 6.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm6.5 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

</style>

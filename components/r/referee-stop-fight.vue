<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xh_on89ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:referee-stop-fight" /></template>
<style>
.xh_on89ge {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 21.5V18c-1.5-1-2-2-3-3.5l-1.75-3a1.5 1.5 0 0 1 2.75-1V6a1.5 1.5 0 0 1 3 0V5a1.5 1.5 0 0 1 3 0v.5a1.5 1.5 0 0 1 3 0V7a1.5 1.5 0 0 1 3 0v8.5c0 1.5-1 2.5-1.5 3v3M10.25 6v4m3-4.5V10m3-3v3.5");
}

</style>

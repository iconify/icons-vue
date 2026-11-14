<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa0rup42w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tachometer" /></template>
<style>
.sa0rup42w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.636 19.614a9 9 0 1 1 12.728 0M3 13.25h2.5m6.5-9v2.5m9 6.5h-2.5m-6.5 0L16.5 10");
}

</style>

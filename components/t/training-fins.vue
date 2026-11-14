<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8_1zfird"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:training-fins" /></template>
<style>
.b8_1zfird {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 19v-5.5l-2.5-10q3.25-1 6.5 0V19a2 2 0 0 1-4 0Zm10 0V3.5q3.25-1 6.5 0l-2.5 10V19a2 2 0 0 1-4 0ZM5 13.5h4m6 0h4");
}

</style>

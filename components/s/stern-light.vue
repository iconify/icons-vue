<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch2o1_b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stern-light" /></template>
<style>
.ch2o1_b0h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 12h16l-1.5 5q-6.5 4-13 0Zm8-3.5V12m-2-5.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM4.5 3L7 4.75M19.5 3L17 4.75");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwij6iu_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:news-source" /></template>
<style>
.qwij6iu_z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 7.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m-3 14c0-4 2.75-6.5 6.5-6.5a7.5 7.5 0 0 1 2.226.325M14 12h5l2.5 2.5V21H14Z");
}

</style>

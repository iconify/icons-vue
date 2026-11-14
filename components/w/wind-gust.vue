<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_-ypj1nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wind-gust" /></template>
<style>
.q_-ypj1nb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8.5h11a2.75 2.75 0 1 0-2.75-2.75M3 12h17M3 15.5h13a2.75 2.75 0 1 1-2.75 2.75");
}

</style>

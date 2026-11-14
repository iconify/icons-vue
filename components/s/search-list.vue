<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfuf9yblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:search-list" /></template>
<style>
.bfuf9yblw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 5h17m-17 5.5H10M3.5 16H8m4-2a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m6 2.5l2.5 2.5");
}

</style>

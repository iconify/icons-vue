<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adx5x3bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:security-light" /></template>
<style>
.adx5x3bti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4v8m5.75-.5a5 5 0 0 1 8.5-5ZM3 8h5.25M10 14l-1.25 6.5m5.75-8L17 19m1.5-9.5l3 5");
}

</style>

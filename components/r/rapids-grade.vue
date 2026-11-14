<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zda95j1ac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rapids-grade" /></template>
<style>
.zda95j1ac {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20h19m-19 0c0-3.5 1.5-4.5 3-4.5s2 1.5 1 2.5m3 2c0-7.5 1.5-9 3.25-9s2.25 2 1 3m2.75 6c0-12 1-15 3-15c1.75 0 2.25 2 1 3");
}

</style>

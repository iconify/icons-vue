<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="litq0obwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:security-guard" /></template>
<style>
.litq0obwm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 7.5L7 3h10l1.5 4.5Zm3 0V10a3.5 3.5 0 0 0 7 0V7.5m-11 14c0-3 3.25-5 7.5-5s7.5 2 7.5 5");
}

</style>

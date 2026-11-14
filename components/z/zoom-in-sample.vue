<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adeh90bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:zoom-in-sample" /></template>
<style>
.adeh90bva {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 10a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0m11.25 4.75l5.75 5.75M10 10h.01");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1uqsm21k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:racing-boots" /></template>
<style>
.c1uqsm21k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5h6.5V11l5.5 2a2.5 2.5 0 0 1 2.5 2.5v5H5Zm0 15h14.5M5 8h6.5");
}

</style>

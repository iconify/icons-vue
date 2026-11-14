<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htogr6j4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-storm" /></template>
<style>
.htogr6j4r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 13.5a3.5 3.5 0 0 1 0-7a5 5 0 0 1 9.5-1a4 4 0 0 1 .5 8Zm5.5 2.75l-2 2.75h3l-2 2.75M7 16.25l-1 3m11.5-3l-1 3");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m30xngm0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:notebook-tabs" /></template>
<style>
.m30xngm0w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 3h7A3.5 3.5 0 0 1 18 6.5v11a3.5 3.5 0 0 1-3.5 3.5h-7A3.5 3.5 0 0 1 4 17.5v-11A3.5 3.5 0 0 1 7.5 3M18 5.5h1.5a1 1 0 0 1 1 1V8a1 1 0 0 1-1 1H18m0 3h1.5a1 1 0 0 1 1 1v1.5a1 1 0 0 1-1 1H18M8 3v18m3-13h4");
}

</style>

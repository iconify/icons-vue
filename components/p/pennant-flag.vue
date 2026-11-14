<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w59u7h1it"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pennant-flag" /></template>
<style>
.w59u7h1it {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5v19M6.14 4.489l7.896 1.805a1.75 1.75 0 0 1 0 3.412L6.14 11.511A1.75 1.75 0 0 1 4 9.805v-3.61a1.75 1.75 0 0 1 2.14-1.706M2.5 21.5h3");
}

</style>

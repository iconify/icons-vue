<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k38c7mb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pharmacy-shelf" /></template>
<style>
.k38c7mb_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 19.5h20m-19.25 0v-10Q2.75 8 4 8V5.5h1.75V8Q7 8 7 9.5v10m2.75 0v-10Q9.75 8 11 8V5.5h1.75V8Q14 8 14 9.5v10m2.75 0v-10Q16.75 8 18 8V5.5h1.75V8Q21 8 21 9.5v10");
}

</style>

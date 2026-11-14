<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jds4-jbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pharmacy-shelf" /></template>
<style>
.jds4-jbzl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 19.5h20m-19.25 0v-10Q2.75 8 4 8V5.5h1.75V8Q7 8 7 9.5v10m2.75 0v-10Q9.75 8 11 8V5.5h1.75V8Q14 8 14 9.5v10m2.75 0v-10Q16.75 8 18 8V5.5h1.75V8Q21 8 21 9.5v10");
}

</style>

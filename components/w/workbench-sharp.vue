<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyhu0gb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:workbench-sharp" /></template>
<style>
.oyhu0gb7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.5h18.5V9H2.75zM5.25 9v12.25M18.75 9v12.25M5.25 17h13.5M8.25 9h7.5v4.5h-7.5zM11 11.25h2");
}

</style>

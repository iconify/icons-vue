<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-khnxb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:road-mud" /></template>
<style>
.s-khnxb8i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 21.5l5.5-19m12.5 19l-5.5-19M12 3v4m-3.75 6q1.25-1.25 2.5 0t2.5 0t2.5 0M7 17.5q1.25-1.25 2.5 0t2.5 0t2.5 0t2.5 0");
}

</style>

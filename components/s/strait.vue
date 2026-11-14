<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z94itj20h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:strait" /></template>
<style>
.z94itj20h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3c6 3 6 15 0 18m19-18c-6 3-6 15 0 18m-12-11q1.25-1.25 2.5 0t2.5 0m-5 4q1.25-1.25 2.5 0t2.5 0");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c87kgvtat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:satellite-terminal" /></template>
<style>
.c87kgvtat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 13l3-8.5h13l-3 8.5Zm5.25 0v4.5L5 20.5h8.5l-3.25-3V13m8-11a3 3 0 0 1 3 3");
}

</style>

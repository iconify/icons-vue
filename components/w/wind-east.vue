<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o17tjq7hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wind-east" /></template>
<style>
.o17tjq7hz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5h19m-3.25-3l3.25 3l-3.25 3M2.5 11H16a3 3 0 1 1-3 3M2.5 16h6a2.75 2.75 0 1 1-2.75 2.75");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-9o_w2uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:number-format" /></template>
<style>
.z-9o_w2uc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 10l2-2v8m3-6a2 2 0 0 1 4 0c0 2.5-4 3.75-4 6h4m3-8H20l-2.25 3.5a2.25 2.25 0 1 1-1.5 3.25");
}

</style>

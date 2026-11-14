<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-cg7jcsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:street-tree" /></template>
<style>
.v-cg7jcsl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 15a3.5 3.5 0 0 1-1-6.5a5.75 5.75 0 0 1 11 0a3.5 3.5 0 0 1-1 6.5Zm4.5 0v6m0-3l3-3m-8 6h10");
}

</style>

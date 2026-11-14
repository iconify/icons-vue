<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp95jqbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:warehouse-shelf" /></template>
<style>
.hp95jqbyf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 21V3.5M20 21V3.5M4 9h16M4 15h16M4 20.5h16M8 5h1a1.5 1.5 0 0 1 1.5 1.5v1A1.5 1.5 0 0 1 9 9H8a1.5 1.5 0 0 1-1.5-1.5v-1A1.5 1.5 0 0 1 8 5m6.5 6h2a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5h-2a1.5 1.5 0 0 1-1.5-1.5v-1a1.5 1.5 0 0 1 1.5-1.5");
}

</style>

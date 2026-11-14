<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwqub4b9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:warehouse-camera" /></template>
<style>
.iwqub4b9q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 6h7a3.5 3.5 0 0 1 3.5 3.5v2A3.5 3.5 0 0 1 14 15H7a3.5 3.5 0 0 1-3.5-3.5v-2A3.5 3.5 0 0 1 7 6m10.5 2.5l4-2v8l-4-2M9 15v4m-4 0h8");
}

</style>

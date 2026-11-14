<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1e9nsbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-construction" /></template>
<style>
.c1e9nsbpy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 21V2.5m-4.5 4H21m-14-4l8 4m0 0v6a1.75 1.75 0 1 1-3.5 0M4 21h6m9 1l-2.25-2.75a2.75 2.75 0 1 1 4.5 0Z");
}

</style>

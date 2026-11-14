<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk0n9mbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:motion-blur" /></template>
<style>
.sk0n9mbtj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 12a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0M2.5 12h5m-3-4H8m-3.5 8H8");
}

</style>

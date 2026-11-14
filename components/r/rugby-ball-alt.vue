<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qh67_vbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rugby-ball-alt" /></template>
<style>
.qh67_vbal {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a10.25 10.25 0 0 1 19 0a10.25 10.25 0 0 1-19 0ZM8 12h8m-7-1.5v3m3-3v3m3-3v3");
}

</style>

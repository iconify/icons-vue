<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m062-e42u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sre" /></template>
<style>
.m062-e42u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 11.5a8 8 0 0 1 16 0m-8 0L15.5 8m-9.75 7h12.5A2.75 2.75 0 0 1 21 17.75a2.75 2.75 0 0 1-2.75 2.75H5.75A2.75 2.75 0 0 1 3 17.75A2.75 2.75 0 0 1 5.75 15M7 17.75h.01");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4283v3at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:setup-sliders" /></template>
<style>
.m4283v3at {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5h10.25m4.5 0h4.25M2.5 12h3.25m4.5 0H21.5m-19 7.5h12.25m4.5 0h2.25m-8.75-15a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m-7 7.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m9 7.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

</style>

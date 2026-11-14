<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfbigkxbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:microscope-light" /></template>
<style>
.hfbigkxbf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 2.5h1a1.75 1.75 0 0 1 1.75 1.75v4A1.75 1.75 0 0 1 9.75 10h-1A1.75 1.75 0 0 1 7 8.25v-4A1.75 1.75 0 0 1 8.75 2.5M11.5 5c6 0 8 8.5 4 13v3m-11-2.75h8.25M4.5 21H19M7.75 12.75l-1.5 2.75m4.5-2.75l1.5 2.75");
}

</style>

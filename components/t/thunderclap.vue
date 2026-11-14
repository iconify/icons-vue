<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oh5u_981a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:thunderclap" /></template>
<style>
.oh5u_981a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 11.5h8.5a3.5 3.5 0 0 0 0-7A4.75 4.75 0 0 0 7 5a3.25 3.25 0 0 0 0 6.5Zm5.5 2.5L10 17.75h4l-2.5 3.75m7.428-8a8 8 0 0 1 0 8");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-a_1k4oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:speaker-smart" /></template>
<style>
.z-a_1k4oj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3h7a3 3 0 0 1 3 3v12.5a3 3 0 0 1-3 3h-7a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3Zm-3 5.5h13M9 13h6m-6 3.5h6");
}

</style>

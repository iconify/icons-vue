<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h06jkob4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:travel-evacuation" /></template>
<style>
.h06jkob4o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 14a6 4 0 1 0 12 0a6 4 0 1 0-12 0ZM4 6h16m-8 0v4m4.5 3l5-2m-14 8.5H16");
}

</style>

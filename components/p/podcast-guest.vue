<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohsdmok3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:podcast-guest" /></template>
<style>
.ohsdmok3g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 8a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM2.5 21.5c0-4 2.25-6.5 5.5-6.5s5.5 2.5 5.5 6.5M14 4a1.5 1.5 0 0 1 1.5-1.5h5A1.5 1.5 0 0 1 22 4v3.5A1.5 1.5 0 0 1 20.5 9h-4L14 11Zm2 8.5h4v5h-4Zm2 5v4");
}

</style>

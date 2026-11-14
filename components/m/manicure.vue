<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klcrhtmwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:manicure" /></template>
<style>
.klcrhtmwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 10h13v11.5h-13Zm4-7.5h5V10h-5Zm11 1s2 2.5 2 3.75a2 2 0 0 1-4 0c0-1.25 2-3.75 2-3.75Z");
}

</style>

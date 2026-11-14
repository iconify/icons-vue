<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d656ywxjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shift-supervisor" /></template>
<style>
.d656ywxjw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 6.5h1.5a4 4 0 0 1 8 0H16Zm2 0v2a3.5 3.5 0 0 0 7 0v-2M3 21c0-3.5 3.5-6 7.5-6c1.044 0 2.054.17 2.977.484M16.25 16h5.5v5.75h-5.5Zm1.5 0h2.5M18 19h2");
}

</style>

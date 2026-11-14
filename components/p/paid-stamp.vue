<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzjhr79gd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:paid-stamp" /></template>
<style>
.jzjhr79gd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 7a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm1.25 2.5L10 14m3.75-4.5L14 14m-2.2 5H3.5v-5h15.3m-4.05 4l2 2L21 15.75");
}

</style>

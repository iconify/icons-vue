<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2-zcbbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nda-signing" /></template>
<style>
.r2-zcbbus {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9h7.5v6.5H3Zm1.75 0V7a2 2 0 0 1 4 0v2m9.951-.446l2.598 1.5l-4.625 8.011L14 19.696l.076-3.131ZM3 19.75h11");
}

</style>

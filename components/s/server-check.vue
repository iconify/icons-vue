<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3g-lcb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:server-check" /></template>
<style>
.c3g-lcb4l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3.5h18v7H3Zm9.25 10H5a2 2 0 0 0-2 2v3a2 2 0 0 0 2 2h7.25M6.75 7h.01m-.01 10h.01M11.5 7h6m-2.75 11l2 2L21 15.75");
}

</style>

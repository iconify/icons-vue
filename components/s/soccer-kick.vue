<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-cn_8v4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:soccer-kick" /></template>
<style>
.m-cn_8v4m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 4l3.5 7l-1 8.5H11l1.5-2.5l-3-1.5l1-5.5L7 2.5Zm9.5 13a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm1-8l2-2M17 9.5l2-2");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tndfjlb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:margarita-glass" /></template>
<style>
.tndfjlb-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 4h16c0 2.75-2.5 4-5 4c0 2.5-1 4.5-3 4.5s-3-2-3-4.5C6.5 8 4 6.75 4 4Zm8 8.5v8m-4 0h8");
}

</style>

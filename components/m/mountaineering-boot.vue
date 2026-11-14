<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p--c7lb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mountaineering-boot" /></template>
<style>
.p--c7lb5o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 16.5V3H12v8l4.5 1.5c1.75.5 2.5 2.25 2.5 4m-15 0h16.5v4H4Zm1.5-7l6.5-2");
}

</style>

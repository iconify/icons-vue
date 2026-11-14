<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msslbrbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smoke-haze" /></template>
<style>
.msslbrbxt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6C4 4 5 4 6.5 6s2.5 2 4 0s2.5-2 4 0s2.5 2 4 0m-11 6c1.5-2 2.5-2 4 0s2.5 2 4 0s2.5-2 4 0m-14 6c1.5-2 2.5-2 4 0s2.5 2 4 0s2.5-2 4 0s2.5 2 4 0");
}

</style>

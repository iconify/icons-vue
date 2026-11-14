<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjyw9qshe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:transplanting-trowel" /></template>
<style>
.yjyw9qshe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 7.75Q17 4.5 21 3q-1.5 4-4.75 9.25ZM14 10l-2.75 2.75m-.922-1.2l2.122 2.122l-7.778 7.778l-2.122-2.122Z");
}

</style>

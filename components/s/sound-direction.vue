<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltgtpxt4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sound-direction" /></template>
<style>
.ltgtpxt4q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 12h.01m2.561-3.064a4 4 0 0 1 0 6.128m2.571-9.192a8 8 0 0 1 0 12.256M15.5 12H21m-3-3l3 3l-3 3");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywicr3bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:poll-anonymous" /></template>
<style>
.ywicr3bcn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3h17v4h-17Zm0 6.75h11v4h-11Zm0 6.75h7v4h-7Zm12 1.5c1.25-2 2.5-2.75 3.5-2.75s2.25.75 3.5 2.75c-1.25 2-2.5 2.75-3.5 2.75S15.75 20 14.5 18Zm.5 3.5l6-7");
}

</style>

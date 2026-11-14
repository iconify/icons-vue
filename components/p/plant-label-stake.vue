<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnfm0xyju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plant-label-stake" /></template>
<style>
.xnfm0xyju {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 2.5H21V8h-8.5ZM16.75 8v13.5m-14.25 0h19M7 21.5V16c-.25-2.75-2-4.5-4.25-4.5C2.75 14 4.5 16 7 16c.25-3 2-5 4.5-5c0 2.75-1.75 5-4.5 5");
}

</style>

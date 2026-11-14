<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w--pykptk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wind-pump" /></template>
<style>
.w--pykptk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 8V2.5M9 8l4.75 2.75M9 8l-4.75 2.75M5.5 21.5L9 8l3.5 13.5M18 14l2.5 3.25a3 3 0 1 1-5 0Z");
}

</style>

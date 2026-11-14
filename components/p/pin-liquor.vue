<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb9f7ob3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-liquor" /></template>
<style>
.cb9f7ob3g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.5h4v5c0 1 3 2 3 4.5v8a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 7 20v-8c0-2.5 3-3.5 3-4.5ZM7 14h10M7 18h10");
}

</style>

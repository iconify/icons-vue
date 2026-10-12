<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyn_dfbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:memory-forget-sharp" /></template>
<style>
.dyn_dfbld {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 21.25v-5.1a7.25 7.25 0 1 1 11.5-5.9l1.75 3.1l.52.901l-1.04-.001h-1.23v4.5H14.5v2.5ZM8.75 8l4.5 4.5m0-4.5l-4.5 4.5");
}

</style>

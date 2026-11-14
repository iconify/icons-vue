<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sz113xbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:small-intestine" /></template>
<style>
.sz113xbyp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4h13c3.75 0 3.75 5 0 5h-9c-3.25 0-3.25 4.5 0 4.5h10c3.25 0 3.25 5 0 5H6c-1.75 0-2.5 1-2.5 3M3.5 4h.01");
}

</style>

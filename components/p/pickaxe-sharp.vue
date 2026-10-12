<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1epb4b8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pickaxe-sharp" /></template>
<style>
.j1epb4b8m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.82 3.55q14.7-.32 14.38 14.38a1.6 1.6 0 0 1-3.2-.11q.53-11.6-11.07-11.07a1.6 1.6 0 0 1-.11-3.2Zm8.68 5.7L3.25 20.5");
}

</style>

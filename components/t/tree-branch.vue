<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-1im0b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tree-branch" /></template>
<style>
.z-1im0b-d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.5v19m0-9.5L13 7.5l2 1.25L3.5 17.5m9.5-10l2.5-4m0 0c1-1.5 4-1.5 5 0c-1 1.5-4 1.5-5 0ZM15 8.75c1.75-1.25 4.5-.25 5.5 2.25c-2.5.25-4.75-.5-5.5-2.25Z");
}

</style>

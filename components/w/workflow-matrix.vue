<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gitegueev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:workflow-matrix" /></template>
<style>
.gitegueev {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h6v6h-6Zm13 0h6v6h-6Zm0 13h6v6h-6Zm-13 0h6v6h-6Zm6-10h7m-2-2l2 2l-2 2m5 1v7m-2-2l2 2l2-2m-5 5h-7m2-2l-2 2l2 2");
}

</style>

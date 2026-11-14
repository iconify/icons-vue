<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmmo1hbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:worry-list" /></template>
<style>
.nmmo1hbxg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 5v-.5A1.5 1.5 0 0 1 8 3h4a1.5 1.5 0 0 1 1.5 1.5V5h1a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2h-9a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2Zm0 5.5h7m-7 3.5h7m-7 3.5h4M20 13v4.5m0 3.25h.01");
}

</style>

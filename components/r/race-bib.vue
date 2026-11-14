<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i5j_hzblv"/><path class="tmxz9fb7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:race-bib" /></template>
<style>
.i5j_hzblv {
  d: path("M3 4.5h18v15H3Zm3 3h.01M18 7.5h.01M6 16.5h.01m11.99 0h.01");
}

.tmxz9fb7t {
  d: path("M9.5 9H13l-2.5 6M15 9v6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hmcwucy7w"/><path class="vcul2lbec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:markdown-rate" /></template>
<style>
.hmcwucy7w {
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 1 0-18 0Zm12-3.5l-6 7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vcul2lbec {
  d: path("M8 9a1.25 1.25 0 1 0 2.5 0A1.25 1.25 0 1 0 8 9Zm5.5 6a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

</style>

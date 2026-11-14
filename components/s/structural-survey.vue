<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="asii2ad5h"/><path class="cu4wqrbkh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:structural-survey" /></template>
<style>
.asii2ad5h {
  d: path("M2 9h20v7H2Zm0 10.5h20");
}

.cu4wqrbkh {
  d: path("M9 10.75h6v3.5H9Zm3 1.75h.01M5.5 11v3m13-3v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

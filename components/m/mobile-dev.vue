<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yuil-jh9q"/><path class="neh6wwbra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mobile-dev" /></template>
<style>
.neh6wwbra {
  d: path("m10.5 10l-1.75 2.5L10.5 15m3-5l1.75 2.5L13.5 15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yuil-jh9q {
  d: path("M6 2h12v20H6Zm4.75 3h2.5");
}

</style>

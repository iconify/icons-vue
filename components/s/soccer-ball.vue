<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="h9wjouvon"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:soccer-ball" /></template>
<style>
.h9wjouvon {
  d: path("m12 8.5l3.25 2.5L14 14.75h-4L8.75 11Zm0 0v-6m3.25 8.5L21 9m-7 5.75l3.5 5m-7.5-5l-3.5 5M8.75 11L3 9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdgu3ybil {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="if9i86pgu"/><path class="yavqkz_9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:snow-shovel" /></template>
<style>
.if9i86pgu {
  d: path("m3.75 19l6.5 2.5l2.5-6.75L6 12.5Zm5.5-5.25L13 3.5M11.25 3l3.5 1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yavqkz_9c {
  d: path("M11.5 18c2-2.5 7-2.5 9 3.5");
}

</style>

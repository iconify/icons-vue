<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tve2gfbrx"/><path class="e5j6j6byq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stope" /></template>
<style>
.e5j6j6byq {
  d: path("M7 10h10l-2.5 6.5h-5Z");
}

.tve2gfbrx {
  d: path("M2.5 20.5V8L6 5l3 2l4-3.5l4 3l4.5-2v16Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y7j-dvi-t"/><path class="jhxb62b6e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pickaxe" /></template>
<style>
.jhxb62b6e {
  d: path("M10.5 6h3v15.5h-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y7j-dvi-t {
  d: path("M3 8c4-4 14-4 18 0C17 6.5 7 6.5 3 8Z");
}

</style>

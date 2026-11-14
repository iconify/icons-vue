<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ax85hdbwy"/><path class="ycdxi8bom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vlog" /></template>
<style>
.ax85hdbwy {
  d: path("M2.5 6.5h13v12h-13Zm13 1L21 5v10l-5.5-1.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ycdxi8bom {
  d: path("M6 12.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

</style>

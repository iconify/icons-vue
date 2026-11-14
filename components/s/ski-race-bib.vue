<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kdl7mbcxf"/><path class="wsr9-kbpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ski-race-bib" /></template>
<style>
.kdl7mbcxf {
  d: path("M8 3a4 4 0 0 0 8 0h4l1 18H3L4 3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wsr9-kbpa {
  d: path("M7 9.5h10v6H7Zm-1 8.75h.01m11.99 0h.01");
}

</style>

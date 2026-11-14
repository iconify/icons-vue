<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jeoaurmiu"/><path class="mk8d-lbbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pill-shape-sorter" /></template>
<style>
.jeoaurmiu {
  d: path("M2.5 4.5h19v15h-19Zm9.5 0v15");
}

.mk8d-lbbo {
  d: path("M5 12a2.25 2.25 0 1 0 4.5 0A2.25 2.25 0 1 0 5 12Zm9.75-4.5h4v9h-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

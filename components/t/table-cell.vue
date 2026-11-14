<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a5jk5wbcp"/><path class="xiht9r5_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:table-cell" /></template>
<style>
.a5jk5wbcp {
  d: path("M2.5 3.5h19v17h-19Zm9.5 0v17M2.5 12h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xiht9r5_j {
  fill: currentColor;
  d: path("M15 14.75h3.75v3H15Z");
}

</style>

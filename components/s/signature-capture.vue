<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hz51vnb5y"/><path class="frlhlji3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:signature-capture" /></template>
<style>
.frlhlji3z {
  d: path("M7 14q1.5-4 3 0q1.5 3 3-1h4M7 17h10");
}

.hz51vnb5y {
  d: path("M3.5 4.5h17v15h-17Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nirj1m4jo"/><path class="jco-y_fue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:widget-table" /></template>
<style>
.jco-y_fue {
  d: path("M6 12h12v6.5H6Zm4 0v6.5m4-6.5v6.5m-8-3.25h12");
}

.nirj1m4jo {
  d: path("M2.5 2.5h19v19h-19Zm0 6h19M10 4.5h.01m1.99 0h.01m1.99 0h.01M10 6.5h.01m1.99 0h.01m1.99 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

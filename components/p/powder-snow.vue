<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w8j00abun"/><path class="izn6zub8v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:powder-snow" /></template>
<style>
.izn6zub8v {
  d: path("M2.5 20q3.75-3 7.5 0t7.5 0c1.5-1 3-1.5 4-1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w8j00abun {
  d: path("M12 3v8M8.5 5l7 4m-7 0l7-4m-13 10.5q3.75-3 7.5 0t7.5 0c1.5-1 3-1.5 4-1.5");
}

</style>

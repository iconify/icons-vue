<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v8mkdccho"/><path class="xnyp1tboz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wrestling-mat-circle" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v8mkdccho {
  d: path("M5.5 6h16l-3 12h-16Z");
}

.xnyp1tboz {
  d: path("M7.5 12a4.5 3 0 1 0 9 0a4.5 3 0 1 0-9 0Z");
}

</style>

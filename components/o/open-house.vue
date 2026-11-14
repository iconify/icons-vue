<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lfanfbwnm"/><path class="eh51xac0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:open-house" /></template>
<style>
.eh51xac0u {
  d: path("M15.5 6.5v-3H18v5M10.5 14H12a1.5 1.5 0 0 1 1.5 1.5v4A1.5 1.5 0 0 1 12 21h-1.5A1.5 1.5 0 0 1 9 19.5v-4a1.5 1.5 0 0 1 1.5-1.5m-2.429-.382l-1.25-.515A1.5 1.5 0 0 0 4.75 14.49v3.949a1.5 1.5 0 0 0 1.001 1.414l1.25.441A1.5 1.5 0 0 0 9 18.88v-3.875a1.5 1.5 0 0 0-.929-1.387");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lfanfbwnm {
  d: path("M3.945 10.213L10.32 4.9a2.625 2.625 0 0 1 3.36 0l6.375 5.313A2.63 2.63 0 0 1 21 12.229v6.146A2.625 2.625 0 0 1 18.375 21H5.625A2.625 2.625 0 0 1 3 18.375v-6.146a2.63 2.63 0 0 1 .945-2.016");
}

</style>

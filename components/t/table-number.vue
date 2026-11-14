<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sgzqu0g7f"/><path class="b2melccis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:table-number" /></template>
<style>
.b2melccis {
  d: path("m11 9.5l1.5-.5v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sgzqu0g7f {
  d: path("M7.875 6h8.25a4.375 4.375 0 0 1 4.375 4.375v3.25A4.375 4.375 0 0 1 16.125 18h-8.25A4.375 4.375 0 0 1 3.5 13.625v-3.25A4.375 4.375 0 0 1 7.875 6");
}

</style>

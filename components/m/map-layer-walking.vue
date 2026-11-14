<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll8teqnoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:map-layer-walking" /></template>
<style>
.ll8teqnoa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 4.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM13 9.5l-1.5 5m0 0l3 3l.5 4m-3.5-7l-3.5 7m0-9l2.25-2.5L13 9.5l2.75 3.25");
}

</style>

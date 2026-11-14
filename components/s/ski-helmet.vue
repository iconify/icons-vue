<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="elv-wibvt"/><path class="uj99f9bmz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ski-helmet" /></template>
<style>
.elv-wibvt {
  d: path("M4 18v-4.5a8 8 0 0 1 16 0V18h-3.5v-2.5h-9V18Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uj99f9bmz {
  d: path("M8.75 8.5h6.5A1.75 1.75 0 0 1 17 10.25A1.75 1.75 0 0 1 15.25 12h-6.5A1.75 1.75 0 0 1 7 10.25A1.75 1.75 0 0 1 8.75 8.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d4zguvbno"/><path class="fg35sjhuf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mine-shaft" /></template>
<style>
.d4zguvbno {
  d: path("M2 6h5v15.5h10V6h5M12 2v9");
}

.fg35sjhuf {
  d: path("M11.5 11h1a1.75 1.75 0 0 1 1.75 1.75v1.5A1.75 1.75 0 0 1 12.5 16h-1a1.75 1.75 0 0 1-1.75-1.75v-1.5A1.75 1.75 0 0 1 11.5 11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

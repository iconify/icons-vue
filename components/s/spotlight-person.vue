<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="krmjhpbkz"/><path class="z4h3pdbxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spotlight-person" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.krmjhpbkz {
  d: path("M9 6h6V3.5a1 1 0 0 0-1-1h-4a1 1 0 0 0-1 1zL3.5 21M15 6l5.5 15");
}

.z4h3pdbxv {
  d: path("M10 13a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-2 8c0-2.5 1.75-3.5 4-3.5s4 1 4 3.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="esjpohbje"/><path class="p0c860bsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spread-operator" /></template>
<style>
.esjpohbje {
  d: path("M6.5 3.5h-3v17h3m11-17h3v17h-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p0c860bsy {
  fill: currentColor;
  d: path("M7 12a1 1 0 1 0 2 0a1 1 0 1 0-2 0m4 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0m4 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>

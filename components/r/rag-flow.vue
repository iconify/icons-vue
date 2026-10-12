<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="myhxt4m7z"/><path class="u36qbe4di"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rag-flow" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.myhxt4m7z {
  width: 9px;
  height: 11px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

.u36qbe4di {
  d: path("M5.5 6.25H9m-3.5 3.5H9M13.5 7H15a1.5 1.5 0 0 1 1.5 1.5v2M15 9.25l1.5 1.5l1.5-1.5m-1.5 3.25q.51 3.74 4.25 4.25q-3.74.51-4.25 4.25q-.51-3.74-4.25-4.25q3.74-.51 4.25-4.25");
}

</style>

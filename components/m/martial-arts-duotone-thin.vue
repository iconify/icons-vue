<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dsh6t34ve"/><path class="k187sabpz"/><path class="f8208jb9b"/><path class="mhk3euagx"/><path class="brz3--krt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:martial-arts-duotone-thin" /></template>
<style>
.brz3--krt {
  d: path("m15 14 4 4");
}

.dsh6t34ve {
  fill: currentColor;
  d: path("M9 8v6h6V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.f8208jb9b {
  d: path("M9 8v6h6V8Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k187sabpz {
  d: path("M2 11h20");
}

.mhk3euagx {
  d: path("m9 14 -4 4");
}

</style>

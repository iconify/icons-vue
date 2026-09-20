<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p811yjdmt"/><path class="h5sy48j_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:music-gen-duotone-thin" /></template>
<style>
.h5sy48j_j {
  d: path("m16 9 -4 -4v12a3 3 0 1 1 -6 0 3 3 0 1 1 6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p811yjdmt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 9 -4 -4v12a3 3 0 1 1 -6 0 3 3 0 1 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

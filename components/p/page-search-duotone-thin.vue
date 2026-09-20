<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="itsd58b9q"/><path class="e3d5xob7w"/><path class="jgpu15buw"/><path class="ozi-k-boi"/><path class="pr-75-r8g"/><path class="x72vanbdm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:page-search-duotone-thin" /></template>
<style>
.e3d5xob7w {
  fill: currentColor;
  d: path("M8 13.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.itsd58b9q {
  fill: currentColor;
  d: path("M3 4.5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v15a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jgpu15buw {
  d: path("M3 4.5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v15a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.ozi-k-boi {
  d: path("M3 7h18");
}

.pr-75-r8g {
  d: path("M8 13.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.x72vanbdm {
  d: path("m13 15.5 2.5 2.5");
}

</style>

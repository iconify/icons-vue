<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z7ca-so4r"/><path class="jfx-5ab5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:travel-review-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jfx-5ab5j {
  d: path("m12 8.5 2 2 -2 2 -2 -2Z");
}

.z7ca-so4r {
  d: path("M4 4h16a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2h-7l-5 5v-5H4a2 2 0 0 1 -2 -2V6a2 2 0 0 1 2 -2");
}

</style>

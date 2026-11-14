<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h1v5xw4hb"/><path class="vclzaqops"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sitemap" /></template>
<style>
.h1v5xw4hb {
  d: path("M11.5 3h1A2.5 2.5 0 0 1 15 5.5A2.5 2.5 0 0 1 12.5 8h-1A2.5 2.5 0 0 1 9 5.5A2.5 2.5 0 0 1 11.5 3M5 16za2.5 2.5 0 0 1 2.5 2.5A2.5 2.5 0 0 1 5 21a2.5 2.5 0 0 1-2.5-2.5A2.5 2.5 0 0 1 5 16m7 0za2.5 2.5 0 0 1 2.5 2.5A2.5 2.5 0 0 1 12 21a2.5 2.5 0 0 1-2.5-2.5A2.5 2.5 0 0 1 12 16m7 0za2.5 2.5 0 0 1 2.5 2.5A2.5 2.5 0 0 1 19 21a2.5 2.5 0 0 1-2.5-2.5A2.5 2.5 0 0 1 19 16m-7-8v8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vclzaqops {
  d: path("M5 16v-2a1.5 1.5 0 0 1 1.5-1.5h11A1.5 1.5 0 0 1 19 14v2");
}

</style>

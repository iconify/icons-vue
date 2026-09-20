<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w7o4ylt6h"/><path class="c2k5-kblh"/><path class="d45kg_ien"/><path class="y29zmn0-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:plastic-free-duotone-thin" /></template>
<style>
.c2k5-kblh {
  d: path("M9 8v12h6V8Z");
}

.d45kg_ien {
  d: path("M10.5 8V4h3v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w7o4ylt6h {
  fill: currentColor;
  d: path("M9 8v12h6V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.y29zmn0-m {
  d: path("M5 20 19 6");
}

</style>

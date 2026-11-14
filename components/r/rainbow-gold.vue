<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c3pyddbgv"/><path class="ipz7hbbkr"/><path class="k1wb-5b7d"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rainbow-gold" /></template>
<style>
.c3pyddbgv {
  d: path("M4.5 12.25a8.5 8.5 0 0 1 17 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ipz7hbbkr {
  d: path("M7.25 12.25a5.75 5.75 0 0 1 11.5 0");
}

.k1wb-5b7d {
  d: path("M10 12.25a3 3 0 0 1 6 0m-12.5 3h8l-1 5.25h-6ZM14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

</style>

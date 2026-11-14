<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b5km_rb3o"/><path class="nu1hb54bj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:soccer-player" /></template>
<style>
.b5km_rb3o {
  d: path("M7.5 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0m1.25 5L8 14l-3.5 7M8 14l4.75 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nu1hb54bj {
  d: path("m5 12l3.75-3L13 11.5m2 7.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>

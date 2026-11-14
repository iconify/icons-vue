<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q0gw9bcmv"/><path class="jpe0mub-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:recycling-truck" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jpe0mub-r {
  d: path("M4.5 19.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0m11.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M10.25 7a3.5 3.5 0 0 1 2 3.5m1-1l-1 1l-1-1m-.5 3.75a3.5 3.5 0 0 1-4 0m.5 1.25l-.5-1.25l1.5-.5m-3-2.25a3.5 3.5 0 0 1 2-3.5m-1.5-.25l1.5.25l-.5 1.5");
}

.q0gw9bcmv {
  d: path("M5.125 4h8.25A2.625 2.625 0 0 1 16 6.625v8a2.625 2.625 0 0 1-2.625 2.625h-8.25A2.625 2.625 0 0 1 2.5 14.625v-8A2.625 2.625 0 0 1 5.125 4M16 8h2.5l3 3.5v5.75H16");
}

</style>

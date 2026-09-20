<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n0n63pb2v"/><path class="p3mjlkbpz"/><path class="ij7rtuuan"/><path class="ayvbjgbud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:shared-memory-outline-thin" /></template>
<style>
.ayvbjgbud {
  d: path("M10.5 8h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ij7rtuuan {
  d: path("M13.5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.n0n63pb2v {
  d: path("M4 15v4h16v-4");
}

.p3mjlkbpz {
  d: path("M6.5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>

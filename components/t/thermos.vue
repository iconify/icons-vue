<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o052xgbgt"/><rect class="hf88cqbxv"/><path class="u2_4436em"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:thermos" /></template>
<style>
.hf88cqbxv {
  width: 8px;
  height: 12.5px;
  x: 7px;
  y: 8.75px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o052xgbgt {
  d: path("M8.75 2.75h4.5q.75 0 .87.74l.26 1.52q.12.74-.63.74h-5.5q-.75 0-.63-.74l.26-1.52q.12-.74.87-.74");
}

.u2_4436em {
  d: path("M15 11h1.75a1.5 1.5 0 0 1 1.5 1.5v4a1.5 1.5 0 0 1-1.5 1.5H15");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="x00qgzx7x"/><path class="p--59e50y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:visa-stamp" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p--59e50y {
  d: path("M8.25 6.5h7.5m-7.5 2.75h4.5m-4.64 3.9l6.91-1.22q.98-.17 1.15.81l.53 2.96q.17.98-.81 1.15l-6.91 1.22q-.98.17-1.15-.81L7.3 14.3q-.17-.98.81-1.15m1.64 2.35l4.25-.75");
}

.x00qgzx7x {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 2px;
}

</style>

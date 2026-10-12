<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hrhyb1bxi"/><path class="f79yhxtpm"/><path class="bs4o24bpy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:time-capsule" /></template>
<style>
.bs4o24bpy {
  d: path("M15.75 11v1h.75");
}

.f79yhxtpm {
  d: path("M10 6.5v11m3-5.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hrhyb1bxi {
  width: 18.5px;
  height: 11px;
  x: 2.75px;
  y: 6.5px;
  rx: 5.5px;
}

</style>

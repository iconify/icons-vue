<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dxhh8pb0h"/><rect class="rp0b5wbus"/><path class="zy7rx6bpy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reduce-transparency" /></template>
<style>
.dxhh8pb0h {
  width: 10.75px;
  height: 10.75px;
  x: 10.5px;
  y: 10.5px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rp0b5wbus {
  width: 12px;
  height: 12px;
  x: 2.75px;
  y: 2.75px;
  rx: 2.5px;
}

.zy7rx6bpy {
  d: path("M6 9.5L9.5 6M6 13l7-7");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lv9esmbjh"/><path class="imgkbxbew"/><rect class="ly9a6fprh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:photo-booth" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.imgkbxbew {
  d: path("M10.25 5.75h3.5a1 1 0 0 1 1 1V9.5a1 1 0 0 1-1 1h-3.5a1 1 0 0 1-1-1V6.75a1 1 0 0 1 1-1");
}

.lv9esmbjh {
  width: 11.5px;
  height: 18.5px;
  x: 6.25px;
  y: 2.75px;
  rx: 2px;
}

.ly9a6fprh {
  width: 5.5px;
  height: 4.75px;
  x: 9.25px;
  y: 13.5px;
  rx: 1px;
}

</style>

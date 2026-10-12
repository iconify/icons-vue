<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="f7r42znre"/><circle class="v90gbqbox"/><path class="ogo8abbce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vault" /></template>
<style>
.f7r42znre {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ogo8abbce {
  d: path("M12 12V8.75M12 12l2.81 1.63M12 12l-2.81 1.63");
}

.v90gbqbox {
  cx: 12px;
  cy: 12px;
  r: 6px;
}

</style>

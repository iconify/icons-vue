<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a6ctoz2fm"/><path class="reu_67o6j"/><rect class="cwaj87brh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pond" /></template>
<style>
.a6ctoz2fm {
  d: path("M2.75 17.5a9.25 3.75 0 1 0 18.5 0a9.25 3.75 0 1 0-18.5 0");
}

.cwaj87brh {
  width: 2.5px;
  height: 5px;
  x: 8.25px;
  y: 3px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.reu_67o6j {
  d: path("M9.5 18.25c1.5.75 3.5.75 5 0m-8-3.76c0-2-.5-3.75-1.25-5.25m4.25 4.65V8m7 6.22q0-3.75 1.5-6.75");
}

</style>

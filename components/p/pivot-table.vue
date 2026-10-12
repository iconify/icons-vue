<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="f7r42znre"/><path class="vklqx0bbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pivot-table" /></template>
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

.vklqx0bbh {
  d: path("M9.25 2.75v18.5m-6.5-12h18.5M12.75 13h2.75a2 2 0 0 1 2 2v2.75M14 11.5L12.5 13l1.5 1.5m2 1.75l1.5 1.5l1.5-1.5");
}

</style>

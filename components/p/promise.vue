<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p6ezq4hqm"/><path class="j1t34yoiz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:promise" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j1t34yoiz {
  d: path("M15 2.5v5h5M9 11.75A2.5 2.5 0 1 1 12.5 14c-.75.5-1 1-1 1.75m0 2.75h.01");
}

.p6ezq4hqm {
  d: path("M6.625 2.5h7.288a2.63 2.63 0 0 1 1.856.769l3.462 3.462A2.63 2.63 0 0 1 20 8.587v10.288a2.625 2.625 0 0 1-2.625 2.625H6.625A2.625 2.625 0 0 1 4 18.875V5.125A2.625 2.625 0 0 1 6.625 2.5");
}

</style>

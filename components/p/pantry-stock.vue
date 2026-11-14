<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gfj4scb7h"/><path class="p_ga2m_ee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pantry-stock" /></template>
<style>
.gfj4scb7h {
  d: path("M3 21.5V5a2.5 2.5 0 0 1 2.5-2.5h13A2.5 2.5 0 0 1 21 5v16.5M3 15h18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p_ga2m_ee {
  d: path("M5.75 15v-4.5A1.5 1.5 0 0 1 7.25 9h3a1.5 1.5 0 0 1 1.5 1.5V15m-4.5-8.75h3M14.5 15v-5h3.75v5");
}

</style>

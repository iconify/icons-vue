<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ie9fhtb8y"/><path class="dqh8ebbgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wave-reflection" /></template>
<style>
.dqh8ebbgp {
  d: path("M16.5 5H20v3.5M3 20h18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ie9fhtb8y {
  d: path("m4 5l8 11.5L20 5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v66kzd7uw"/><path class="ceyqjyfpz"/><path class="tacfftb9n"/><path class="fh46dtjbs"/><path class="cj8gecc7a"/><path class="ufjf60bpr"/><path class="cmfydpaql"/><path class="xzo2fg5pj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:skeleton-duotone-thin" /></template>
<style>
.ceyqjyfpz {
  fill: currentColor;
  d: path("M7 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.cj8gecc7a {
  d: path("M7 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.cmfydpaql {
  d: path("M10 17v3");
}

.fh46dtjbs {
  d: path("M5 12a7 7 0 0 1 14 0v3a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tacfftb9n {
  fill: currentColor;
  d: path("M13 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ufjf60bpr {
  d: path("M13 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.v66kzd7uw {
  fill: currentColor;
  d: path("M5 12a7 7 0 0 1 14 0v3a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xzo2fg5pj {
  d: path("M14 17v3");
}

</style>

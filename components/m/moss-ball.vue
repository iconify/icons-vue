<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t7t0gmboe"/><path class="q-rjoqbhi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:moss-ball" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q-rjoqbhi {
  d: path("M14.75 11.25a1.75 1.75 0 0 1 0-3.5m-5.5 9a1.75 1.75 0 0 1 0-3.5");
}

.t7t0gmboe {
  d: path("M20 12a3 3 0 0 1-1.5 4.75a3 3 0 0 1-4 2.75a3 3 0 0 1-5 0a3 3 0 0 1-4-2.75A3 3 0 0 1 4 12a3 3 0 0 1 1.5-4.75a3 3 0 0 1 4-2.75a3 3 0 0 1 5 0a3 3 0 0 1 4 2.75A3 3 0 0 1 20 12");
}

</style>

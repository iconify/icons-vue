<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g6jnqcxeg"/><path class="bt7bxfb3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smart-sprinkler" /></template>
<style>
.bt7bxfb3f {
  d: path("M5 9q4.5-4.5 9.5 2m-.5 6a5.66 5.66 0 0 1 8 0m-6 2a2.83 2.83 0 0 1 4 0m-2 2h.01");
}

.g6jnqcxeg {
  d: path("M5 21.5v-9m-2 0h4V9H3ZM5 9q5-8.5 15.5-.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

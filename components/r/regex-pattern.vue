<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c6ooj5b2j"/><circle class="mmu7nww0a"/><path class="hqdmvkbdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:regex-pattern" /></template>
<style>
.c6ooj5b2j {
  d: path("M4.75 4.75h-1.5v14.5h1.5m14.5-14.5h1.5v14.5h-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hqdmvkbdc {
  d: path("M14.25 6.75v7.5M11 8.63l6.5 3.75m-6.5 0l6.5-3.75");
}

.mmu7nww0a {
  cx: 8px;
  cy: 16px;
  r: 1.25px;
}

</style>

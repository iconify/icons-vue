<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kctvib72p"/><path class="y0_7bcb8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:treasury-multi-entity" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kctvib72p {
  d: path("M9.75 2.5h4.5A1.75 1.75 0 0 1 16 4.25v1.5a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 8 5.75v-1.5A1.75 1.75 0 0 1 9.75 2.5m-5.5 12h1A1.75 1.75 0 0 1 7 16.25v2A1.75 1.75 0 0 1 5.25 20h-1a1.75 1.75 0 0 1-1.75-1.75v-2a1.75 1.75 0 0 1 1.75-1.75m7.25 0h1a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 12.5 20h-1a1.75 1.75 0 0 1-1.75-1.75v-2a1.75 1.75 0 0 1 1.75-1.75m7.25 0h1a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 19.75 20h-1A1.75 1.75 0 0 1 17 18.25v-2a1.75 1.75 0 0 1 1.75-1.75M12 7.5v7");
}

.y0_7bcb8m {
  d: path("M4.75 14.5V11h14.5v3.5");
}

</style>

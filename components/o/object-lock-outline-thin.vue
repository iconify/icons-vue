<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aq1lvs8nn"/><path class="pc5t8x4uc"/><path class="wi-4s5bun"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:object-lock-outline-thin" /></template>
<style>
.aq1lvs8nn {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pc5t8x4uc {
  d: path("M8.5 16.5a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2V19a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

.wi-4s5bun {
  d: path("M9.5 14.5a2.5 2.5 0 0 1 5 0");
}

</style>

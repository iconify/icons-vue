<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="inf4ddb2s"/><path class="o6a500beq"/><path class="m4_8dnm3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:skeleton-key" /></template>
<style>
.inf4ddb2s {
  cx: 12px;
  cy: 6px;
  r: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m4_8dnm3c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.25V21m-2-8.75h4m-2 5.25H8.5M12 21H8.5");
}

.o6a500beq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

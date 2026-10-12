<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="wrc2yvbit"/><path class="x8dr7yu9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wolf" /></template>
<style>
.wrc2yvbit {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 20.5c-.25-3.5 0-6.5 1-9c.5-1.25.5-2.25.25-3.25l.5-3.5c.1-.5.6-.6.9-.2l1.6 2.2L14.5 4c.5-.4 1.25.15.85.75l-2.35 4c.5 1.25 1.5 2.25 2.75 3.5c1 1 1.25 2.5 1.25 4.25v4ZM19.05 3.25a2 2 0 1 0 2.1 2.6a1.75 1.75 0 0 1-2.1-2.6");
}

.x8dr7yu9j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 8h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

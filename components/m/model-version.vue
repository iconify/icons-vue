<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="tjvao7bso"/><path class="xy685abto"/><path class="bythc1b6v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:model-version" /></template>
<style>
.bythc1b6v {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.25 18.5h.01");
}

.tjvao7bso {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.87 3.25l3.76 2.15q.87.5.87 1.5v4.2q0 1-.87 1.5l-3.76 2.15q-.87.5-1.74 0L4.37 12.6q-.87-.5-.87-1.5V6.9q0-1 .87-1.5l3.76-2.15q.87-.5 1.74 0");
}

.xy685abto {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 5.9L9 9.05l5.5-3.15M9 9.05v6.2m4.75.5H17q1 0 1.74.68l1.52 1.39q.74.68 0 1.36l-1.52 1.39q-.74.68-1.74.68h-3.25q-1 0-1-1v-3.5q0-1 1-1");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

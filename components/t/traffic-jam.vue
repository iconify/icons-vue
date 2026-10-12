<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="m_hf9rbrd"/><path class="rky71driu"/><path class="uwj3xm36d"/><path class="m--5damoa"/><path class="o8-81ebgi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:traffic-jam" /></template>
<style>
.m_hf9rbrd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.14 5.33l.72-1.66q.39-.92 1.39-.92h6.5q1 0 1.39.92l.72 1.66q.39.92.39 1.92v1q0 1-1 1h-9.5q-1 0-1-1v-1q0-1 .39-1.92");
}

.m--5damoa {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 16.25h.01m5.49 0h.01");
}

.o8-81ebgi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 19.25v2m7.5-2v2");
}

.rky71driu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.75 6.5h.01m5.49 0h.01");
}

.uwj3xm36d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.14 15.08l.72-1.66q.39-.92 1.39-.92h6.5q1 0 1.39.92l.72 1.66q.39.92.39 1.92v1.25q0 1-1 1h-9.5q-1 0-1-1V17q0-1 .39-1.92");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="bgt9f0b2v"/><path class="uk6150bvj"/><path class="jfkowv6ni"/><path class="n-8662vzm"/><path class="fkc1fublc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:olive-branch-peace" /></template>
<style>
.bgt9f0b2v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 20.75q4-9.75 15.25-16.5");
}

.fkc1fublc {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.5 17.5h.01m2.74-2.25h.01");
}

.jfkowv6ni {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.86 13.43q2.62 2.89 5-.21q-2.63-2.89-5 .21m5.16-5.16q3.08-2.41.16-5q-3.08 2.4-.16 5");
}

.n-8662vzm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.02 8.27q1.98 3.36 4.93.8q-1.98-3.36-4.93-.8");
}

.uk6150bvj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.86 13.43q2.53-2.97-.85-4.93q-2.53 2.98.85 4.93");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

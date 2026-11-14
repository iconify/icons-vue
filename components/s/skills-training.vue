<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pp7ekf9-o"/><path class="vydl-bb6t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:skills-training" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pp7ekf9-o {
  d: path("m6.384 7.143l4.977-2.342a1.5 1.5 0 0 1 1.278 0l4.977 2.342a1.5 1.5 0 0 1 0 2.714l-4.977 2.342a1.5 1.5 0 0 1-1.278 0L6.384 9.857a1.5 1.5 0 0 1 0-2.714M6.5 10v5c0 1.425 2.256 2.85 5.053 2.989m5.947-6.99V10m-13-1v6m12.512-.539za.68.68 0 0 1 .678-.648h.12a.68.68 0 0 1 .678.648a1.19 1.19 0 0 0 .591.973l.013.007a1.19 1.19 0 0 0 1.137.026a.68.68 0 0 1 .901.263l.059.103a.68.68 0 0 1-.222.912a1.19 1.19 0 0 0-.546.998v.014a1.19 1.19 0 0 0 .546.998a.68.68 0 0 1 .222.912l-.059.103a.68.68 0 0 1-.901.263a1.19 1.19 0 0 0-1.137.026l-.013.007a1.19 1.19 0 0 0-.591.973a.68.68 0 0 1-.678.648h-.12a.68.68 0 0 1-.678-.648a1.19 1.19 0 0 0-.591-.973l-.013-.007a1.19 1.19 0 0 0-1.137-.026a.68.68 0 0 1-.901-.263l-.059-.103a.68.68 0 0 1 .222-.912a1.19 1.19 0 0 0 .546-.998v-.014a1.19 1.19 0 0 0-.546-.998a.68.68 0 0 1-.222-.912l.059-.103a.68.68 0 0 1 .901-.263a1.19 1.19 0 0 0 1.137-.026l.013-.007a1.19 1.19 0 0 0 .591-.973");
}

.vydl-bb6t {
  d: path("M16.75 17.75a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>

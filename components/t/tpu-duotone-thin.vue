<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hjy8rqkzo"/><path class="g89aadeaf"/><path class="j6v5-qbsu"/><path class="d68m7u0nn"/><path class="i5z9c0bsl"/><path class="wniafzb5r"/><path class="ao-h93max"/><path class="cdyau8b6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tpu-duotone-thin" /></template>
<style>
.ao-h93max {
  d: path("M9 19v3");
}

.cdyau8b6j {
  d: path("M15 19v3");
}

.d68m7u0nn {
  d: path("M9.5 12A2.5 2.5 0 0 1 12 9.5a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5A2.5 2.5 0 0 1 9.5 12");
}

.g89aadeaf {
  fill: currentColor;
  d: path("M9.5 12A2.5 2.5 0 0 1 12 9.5a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5A2.5 2.5 0 0 1 9.5 12");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hjy8rqkzo {
  fill: currentColor;
  d: path("M5 7a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i5z9c0bsl {
  d: path("M9 2v3");
}

.j6v5-qbsu {
  d: path("M5 7a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.wniafzb5r {
  d: path("M15 2v3");
}

</style>

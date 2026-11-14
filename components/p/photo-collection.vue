<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d9n3tt2xg"/><path class="mq_1f0bod"/><path class="aed39ydsm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:photo-collection" /></template>
<style>
.aed39ydsm {
  d: path("M8 5.75V5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v7.5a2 2 0 0 1-2 2h-.75M2.5 18L7 13.5l4 4m1.5-5.25h.01");
}

.d9n3tt2xg {
  d: path("M6 8.5h7a3.5 3.5 0 0 1 3.5 3.5v4.5A3.5 3.5 0 0 1 13 20H6a3.5 3.5 0 0 1-3.5-3.5V12A3.5 3.5 0 0 1 6 8.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mq_1f0bod {
  d: path("M5.25 8.5v-.75a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v7.5a2 2 0 0 1-2 2h-.75");
}

</style>

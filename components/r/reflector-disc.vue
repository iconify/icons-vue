<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="byxvskbyl"/><circle class="b2lkeqpus"/><path class="xstyffvge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reflector-disc" /></template>
<style>
.b2lkeqpus {
  cx: 10px;
  cy: 10px;
  r: 3.5px;
}

.byxvskbyl {
  cx: 10px;
  cy: 10px;
  r: 6px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xstyffvge {
  d: path("M10 16v5.25m8.5-13.5l2.75-1.5m-2.75 6l2.75 1.5");
}

</style>

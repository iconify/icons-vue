<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ihzjn8lcj"/><rect class="ylab9mpbb"/><path class="a6nzcybge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pickup-store" /></template>
<style>
.a6nzcybge {
  d: path("M12 13.75v1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ihzjn8lcj {
  d: path("M5.4 2.75h13.2a1.5 1.5 0 0 1 1.4.97l1.25 2.03v.5a2 2 0 0 1-2 2H4.75a2 2 0 0 1-2-2v-.5L4 3.72a1.5 1.5 0 0 1 1.4-.97m3.85 0l-.5 5.5m6-5.5l.5 5.5m-10.5 2.5h14.5v8.5a2 2 0 0 1-2 2H6.75a2 2 0 0 1-2-2Z");
}

.ylab9mpbb {
  width: 4.5px;
  height: 4.5px;
  x: 9.75px;
  y: 13.75px;
  rx: 1px;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xyhb5lbyc"/><path class="rh19cybbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:team-hierarchy" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rh19cybbm {
  d: path("M3.5 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0m13 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.xyhb5lbyc {
  d: path("M9.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-2 7.5c.25-1.4 2.1-2.25 4.5-2.25s4.25.85 4.5 2.25m-4.5 0V15m-6.5 2v-.5A1.5 1.5 0 0 1 7 15h10a1.5 1.5 0 0 1 1.5 1.5v.5");
}

</style>

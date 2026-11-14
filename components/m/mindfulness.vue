<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mfw8gbgyh"/><path class="dmqe0phlg"/><path class="ope9k8wdx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mindfulness" /></template>
<style>
.dmqe0phlg {
  d: path("M11.75 7c1.25 1 1.25 3 0 4.5C10.5 10 10.5 8 11.75 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mfw8gbgyh {
  d: path("M8 21v-3.5c-2.5-1.75-3.5-4.25-3.5-7C4.5 6.25 7.75 3 12 3c4 0 7 2.75 7 6.75l1.5 3.5c.25.5 0 1-.75 1H19v2.25a2 2 0 0 1-2 2h-2V21");
}

.ope9k8wdx {
  d: path("M11.75 11.5c-1.5 0-3-1-3.5-2.5c1.5 0 3 1 3.5 2.5m0 0c1.5 0 3-1 3.5-2.5c-1.5 0-3 1-3.5 2.5");
}

</style>

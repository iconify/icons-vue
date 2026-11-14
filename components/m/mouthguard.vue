<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k8vv0mwwh"/><path class="qaxgs-v7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mouthguard" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k8vv0mwwh {
  d: path("M3 9c0 6 4 9 9 9s9-3 9-9a2.25 2.25 0 0 0-4.5 0A2.25 2.25 0 0 0 12 9a2.25 2.25 0 0 0-4.5 0A2.25 2.25 0 0 0 3 9");
}

.qaxgs-v7v {
  d: path("M6.5 12c1 2 3 2.75 5.5 2.75S16.5 14 17.5 12");
}

</style>

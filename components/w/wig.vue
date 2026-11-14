<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ocyf5ip6z"/><path class="v0gavjbjl"/><path class="tpnkrcc7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wig" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ocyf5ip6z {
  d: path("M8 21.5v-4c-2.5-1.75-3.5-4.25-3.5-7C4.5 6.25 7.75 3 12 3c4 0 7 2.75 7 6.75l1.5 3.5c.25.5-.1 1-.75 1H19v2.25c0 1.1-.9 2-2 2h-2v3");
}

.tpnkrcc7x {
  d: path("M5.5 21.5h12M16.75 11h.01");
}

.v0gavjbjl {
  fill: currentColor;
  d: path("M4.25 14c-1-3-.5-7.75 2.75-9.75C9.5 2.5 14.5 2.5 17 4.5c1 1 1.75 2.25 2 3.5c-3-1.25-6.5-1-8.5.25c-1.5 1-1.75 3-1.25 5.25c.25 1.5-.5 3-2 3c-1.75 0-2.5-1-3-2.5");
}

</style>

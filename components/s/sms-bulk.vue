<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zhan4ybcl"/><path class="q5y7g7bqq"/><path class="htjynnbvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sms-bulk" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.htjynnbvq {
  d: path("M8.5 6.5v-1a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2h-1M5.5 14h.01m2.99 0h.01m2.99 0h.01");
}

.q5y7g7bqq {
  d: path("M5.5 9.5v-1a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2h-1");
}

.zhan4ybcl {
  d: path("M2.5 11.5a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2H9l-3.5 2v-2h-1a2 2 0 0 1-2-2Z");
}

</style>

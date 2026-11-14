<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q-qump_tv"/><path class="qjg_o9u4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pill-round" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q-qump_tv {
  d: path("M3 10a9 4 0 1 0 18 0a9 4 0 1 0-18 0");
}

.qjg_o9u4m {
  d: path("M3 10v4a9 4 0 0 0 18 0v-4");
}

</style>

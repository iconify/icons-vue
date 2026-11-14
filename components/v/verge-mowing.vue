<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pdikfmo8c"/><path class="b8m_d26oo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:verge-mowing" /></template>
<style>
.b8m_d26oo {
  d: path("M4 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m6.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pdikfmo8c {
  d: path("M5 11.5h7.5A2.5 2.5 0 0 1 15 14a2.5 2.5 0 0 1-2.5 2.5H5A2.5 2.5 0 0 1 2.5 14A2.5 2.5 0 0 1 5 11.5m8 0l5.5-8h3");
}

</style>

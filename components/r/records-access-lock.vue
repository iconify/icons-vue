<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="szi_5csbx"/><path class="oopempb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:records-access-lock" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oopempb9x {
  d: path("M5 13.5h2.5L9 11l2 5.5l1.5-3h1m3 3.75h3A1.75 1.75 0 0 1 21.25 19v1a1.75 1.75 0 0 1-1.75 1.75h-3A1.75 1.75 0 0 1 14.75 20v-1a1.75 1.75 0 0 1 1.75-1.75m-.25 0V16c0-1 .75-1.75 1.75-1.75s1.75.75 1.75 1.75v1.25");
}

.szi_5csbx {
  d: path("M12.007 20.5H4.5c-1.1 0-2-.9-2-2v-13c0-1.1.9-2 2-2H9l2 2h8.5c1.1 0 2 .9 2 2v5.552M2.5 8.75h19");
}

</style>

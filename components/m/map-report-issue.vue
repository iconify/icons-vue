<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o9g5yj2rw"/><path class="kv74_e5bn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:map-report-issue" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kv74_e5bn {
  d: path("m18.862 14.951l2.156 4.67a1.5 1.5 0 0 1-1.362 2.129h-4.312a1.5 1.5 0 0 1-1.362-2.129l2.156-4.67a1.5 1.5 0 0 1 2.724 0m-1.362.799v2m0 2h.01");
}

.o9g5yj2rw {
  d: path("M11.129 19.251L8.5 18.5l-6 2v-15l6-2l7 2l6-2v10.571M9 3.5V18");
}

</style>

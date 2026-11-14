<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yep_gebsk"/><path class="h11fedc8z"/><path class="ev_0jfbfy"/><path class="i-pz51w1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:school-nearby" /></template>
<style>
.ev_0jfbfy {
  fill: currentColor;
  d: path("M11 7.75c0-1.25.25-2 1-2s1 .75 1 2Z");
}

.h11fedc8z {
  d: path("M9.75 9.25V4.5h4.5v4.75M9 4.5l3-2l3 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-pz51w1f {
  d: path("M10 21.5v-5h4v5m-9-5h.01m13.99 0h.01");
}

.yep_gebsk {
  d: path("M2.5 20v-5.5A1.5 1.5 0 0 1 4 13h2a1 1 0 0 0 1-1v-.219a1.5 1.5 0 0 1 .64-1.229l3.5-2.45a1.5 1.5 0 0 1 1.72 0l3.5 2.45a1.5 1.5 0 0 1 .64 1.229V12a1 1 0 0 0 1 1h2a1.5 1.5 0 0 1 1.5 1.5V20a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 20");
}

</style>

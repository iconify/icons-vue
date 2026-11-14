<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jkvxadb0n"/><path class="ihp6nfbah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tanker-truck" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ihp6nfbah {
  d: path("M15.5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-13-4H16");
}

.jkvxadb0n {
  d: path("M2 10a7 4.5 0 1 0 14 0a7 4.5 0 1 0-14 0m14-2h3l2.5 4v4.5H16m-12 2a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>

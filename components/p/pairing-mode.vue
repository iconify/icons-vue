<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b_ulcfb9d"/><path class="h75x1qbrx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pairing-mode" /></template>
<style>
.b_ulcfb9d {
  d: path("M9.5 17.5a5.5 5.5 0 1 1 4.25-3.5");
}

.h75x1qbrx {
  d: path("M14.5 6.5a5.5 5.5 0 1 1-4.25 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

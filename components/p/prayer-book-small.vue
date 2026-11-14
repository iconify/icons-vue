<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f0siqlqks"/><path class="totmgg2vb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:prayer-book-small" /></template>
<style>
.f0siqlqks {
  d: path("M5 15.5V5a2.5 2.5 0 0 1 2.5-2.5H19V18H7.5A2.5 2.5 0 0 1 5 15.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.totmgg2vb {
  d: path("M5 15.5A2.5 2.5 0 0 1 7.5 13H19m-6 5v3.5l1.5-1.25L16 21.5V18");
}

</style>

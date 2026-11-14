<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p4a-_ktdj"/><path class="kzp_6_b6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:printmaking-stamp" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kzp_6_b6q {
  d: path("m10.25 8.5l-.5 4H5A1.5 1.5 0 0 0 3.5 14v2.5h17V14a1.5 1.5 0 0 0-1.5-1.5h-4.75l-.5-4M5 20h14");
}

.p4a-_ktdj {
  d: path("M9 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>

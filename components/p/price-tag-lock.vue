<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r5ows415v"/><path class="w71aie9fj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:price-tag-lock" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r5ows415v {
  d: path("M9.905 4.5h6.97A2.625 2.625 0 0 1 19.5 7.125v9.75a2.625 2.625 0 0 1-2.625 2.625h-6.97a2.63 2.63 0 0 1-2.184-1.169l-3.25-4.875a2.625 2.625 0 0 1 0-2.912l3.25-4.875A2.63 2.63 0 0 1 9.905 4.5M8.25 12h.01");
}

.w71aie9fj {
  d: path("M13.25 12h2A1.75 1.75 0 0 1 17 13.75v.5A1.75 1.75 0 0 1 15.25 16h-2a1.75 1.75 0 0 1-1.75-1.75v-.5A1.75 1.75 0 0 1 13.25 12m-.5 0v-1a1.5 1.5 0 0 1 3 0v1");
}

</style>

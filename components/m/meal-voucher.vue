<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n9-5c5bbt"/><path class="djg1i45mc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:meal-voucher" /></template>
<style>
.djg1i45mc {
  d: path("M7.5 10.5c0 1.25 3 1.25 3 0m-1.5 1V16m6-2.75V16m0-2.75V8c1.5.75 2 2.75 1.5 5.25Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n9-5c5bbt {
  d: path("M3 5.5h18V10a2 2 0 0 0 0 4v4.5H3V14a2 2 0 0 0 0-4ZM7.5 8v2.5M9 8v2.5M10.5 8v2.5");
}

</style>

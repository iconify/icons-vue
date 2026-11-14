<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bp8v15b4h"/><path class="b2sy9c4co"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:prostate" /></template>
<style>
.b2sy9c4co {
  fill: currentColor;
  d: path("M7.5 14a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.bp8v15b4h {
  d: path("M3.5 14a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0m11.25-4.75L20.5 3.5m-5 0h5v5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

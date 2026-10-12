<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="m1r5rg96a"/><path class="nbhpv31pe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:studio-light" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m1r5rg96a {
  width: 12px;
  height: 8px;
  x: 2.75px;
  y: 5.75px;
  rx: 2px;
}

.nbhpv31pe {
  d: path("M6.25 8.5V11m3-2.5V11m5.5-5.25l6.5-3m-6.5 11l6.5 3m-12.5-3v7.5m-3.75 0h7.5");
}

</style>

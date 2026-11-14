<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bup7c2bea"/><path class="c93gw0bfw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:work-anniversary" /></template>
<style>
.bup7c2bea {
  d: path("M6 15a6 6 0 1 0 12 0a6 6 0 1 0-12 0M7.5 2.5l3.25 6.75M16.5 2.5l-3.25 6.75");
}

.c93gw0bfw {
  d: path("M14 11.75h-3.25l-.25 2.75c1.5-.5 3.25 0 3.25 1.75c0 1.5-1.25 2-2.5 1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

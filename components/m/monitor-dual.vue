<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ygpsmtbul"/><path class="vpo1iqsnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:monitor-dual" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vpo1iqsnq {
  d: path("M5 14h-.5a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2H15m-.25 13v3.5m-3 0h6");
}

.ygpsmtbul {
  d: path("M11.5 8H18a3.5 3.5 0 0 1 3.5 3.5v2A3.5 3.5 0 0 1 18 17h-6.5A3.5 3.5 0 0 1 8 13.5v-2A3.5 3.5 0 0 1 11.5 8");
}

</style>

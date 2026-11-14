<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s8v_0ybdy"/><path class="ft64jibva"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rocket-plus" /></template>
<style>
.ft64jibva {
  d: path("M7.5 9.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M18 15v6m-3-3h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s8v_0ybdy {
  d: path("M9 2.5q3.75 3 3.75 7.5v6h-7.5v-6q0-4.5 3.75-7.5m-3.75 8L2.75 13v2l2.5-1m7.5-3.5l2.5 2.5v1.864m-.06.112L12.75 14");
}

</style>

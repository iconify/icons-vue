<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z-x-qzb5v"/><path class="c_xarrb-e"/><path class="r8v41n4zk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:necklace-bust" /></template>
<style>
.c_xarrb-e {
  d: path("M8.25 9c.5 3 2.25 4.75 3.75 5.25c1.5-.5 3.25-2.25 3.75-5.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r8v41n4zk {
  d: path("M10.75 15.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.z-x-qzb5v {
  d: path("M8 2.5V7c0 2-3 3-5 4.5v10h18v-10C19 10 16 9 16 7V2.5");
}

</style>

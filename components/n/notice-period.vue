<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zsue4nw4g"/><path class="wnpvydm_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:notice-period" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wnpvydm_x {
  d: path("m4.5 3.5l1.171.585A1.5 1.5 0 0 1 6.5 5.427v13.146a1.5 1.5 0 0 1-.829 1.342L4.5 20.5a1.382 1.382 0 0 1-2-1.236V4.736a1.382 1.382 0 0 1 2-1.236m8 11.75a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0M17 8v2.75M15.5 8h3M17 15.25v-2.5");
}

.zsue4nw4g {
  d: path("M2.5 21.5v-18a1 1 0 0 1 1-1h5a1 1 0 0 1 1 1v18");
}

</style>

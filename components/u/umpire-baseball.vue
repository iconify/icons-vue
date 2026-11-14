<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lekpozb-o"/><path class="unr8p9i_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:umpire-baseball" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lekpozb-o {
  d: path("M12 2.5za5 5 0 0 1 5 5V8a5 5 0 0 1-5 5a5 5 0 0 1-5-5v-.5a5 5 0 0 1 5-5m-8 19c0-3 3.5-5.5 8-5.5s8 2.5 8 5.5M7 7h10m-6.5 0v6m3-6v6");
}

.unr8p9i_x {
  d: path("M8.5 16.75v1.75a3.5 3 0 0 0 7 0v-1.75");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv_zk-d0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mine-radio" /></template>
<style>
.lv_zk-d0f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 9.5h2A3.5 3.5 0 0 1 12 13v5a3.5 3.5 0 0 1-3.5 3.5h-2A3.5 3.5 0 0 1 3 18v-5a3.5 3.5 0 0 1 3.5-3.5m-.5 0V3m8.75 8a3.5 3.5 0 0 1 0 4M17 9.5a6.25 6.25 0 0 1 0 7m2.25-8.75a9 9 0 0 1 0 10.5");
}

</style>

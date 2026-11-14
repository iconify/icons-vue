<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pv0zd0bxe"/><path class="wqvooebbw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rx-generic" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pv0zd0bxe {
  d: path("M6.75 12za2.75 2.75 0 0 1 2.75 2.75v4a2.75 2.75 0 0 1-2.75 2.75A2.75 2.75 0 0 1 4 18.75v-4A2.75 2.75 0 0 1 6.75 12m10.5 0zA2.75 2.75 0 0 1 20 14.75v4a2.75 2.75 0 0 1-2.75 2.75a2.75 2.75 0 0 1-2.75-2.75v-4A2.75 2.75 0 0 1 17.25 12M4 17.75l5.5-2.5m5 2.5l5.5-2.5M6.5 9a5.5 5.5 0 0 1 11 0");
}

.wqvooebbw {
  d: path("M15.25 6.75L17.5 9l2.25-2.25");
}

</style>

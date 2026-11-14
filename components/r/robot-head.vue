<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ybavqlu3g"/><path class="z_xhfob3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:robot-head" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ybavqlu3g {
  d: path("M8.375 7h7.25A4.375 4.375 0 0 1 20 11.375v5.25A4.375 4.375 0 0 1 15.625 21h-7.25A4.375 4.375 0 0 1 4 16.625v-5.25A4.375 4.375 0 0 1 8.375 7M12 4.75V7m-1.25-3.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.z_xhfob3z {
  d: path("M8.75 10.5za1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 8.75 14A1.75 1.75 0 0 1 7 12.25a1.75 1.75 0 0 1 1.75-1.75m6.5 0zA1.75 1.75 0 0 1 17 12.25A1.75 1.75 0 0 1 15.25 14a1.75 1.75 0 0 1-1.75-1.75a1.75 1.75 0 0 1 1.75-1.75M9 17.5h6");
}

</style>

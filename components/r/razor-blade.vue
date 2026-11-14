<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h08zulttp"/><path class="kmnkxpx7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:razor-blade" /></template>
<style>
.h08zulttp {
  d: path("M6.125 7h11.75A2.625 2.625 0 0 1 20.5 9.625v4.75A2.625 2.625 0 0 1 17.875 17H6.125A2.625 2.625 0 0 1 3.5 14.375v-4.75A2.625 2.625 0 0 1 6.125 7M7 12h10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kmnkxpx7j {
  d: path("M6 12a1 1 0 1 0 2 0a1 1 0 1 0-2 0m10 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>

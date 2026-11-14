<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="boj3k0b7v"/><path class="e0w4zj40u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spring-sprout" /></template>
<style>
.boj3k0b7v {
  d: path("M4 20.5c1.5-4 14.5-4 16 0Z");
}

.e0w4zj40u {
  d: path("M12 17.5v-7c0-4 2.5-6.5 7-6.5c0 4-2.5 6.5-7 6.5m0 3c-4 0-7-2-7-6c4 0 6.5 2 7 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

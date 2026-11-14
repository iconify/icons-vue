<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yssyf8lqd"/><path class="q0x_emb9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:radio-station" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q0x_emb9f {
  d: path("M8 11.5a4 4 0 0 1 8 0m-8 0zA1.5 1.5 0 0 1 9.5 13v.5A1.5 1.5 0 0 1 8 15a1.5 1.5 0 0 1-1.5-1.5V13A1.5 1.5 0 0 1 8 11.5m8 0za1.5 1.5 0 0 1 1.5 1.5v.5A1.5 1.5 0 0 1 16 15a1.5 1.5 0 0 1-1.5-1.5V13a1.5 1.5 0 0 1 1.5-1.5");
}

.yssyf8lqd {
  d: path("M6.875 4.5h10.25A4.375 4.375 0 0 1 21.5 8.875v6.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 15.125v-6.25A4.375 4.375 0 0 1 6.875 4.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ajr9e2b3x"/><circle class="zgau9oblh"/><path class="ojqgu4b9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:notification-square" /></template>
<style>
.ajr9e2b3x {
  d: path("M11.75 6.25h-6a3 3 0 0 0-3 3v9a3 3 0 0 0 3 3h9a3 3 0 0 0 3-3v-6a6.25 6.25 0 0 1-6-6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ojqgu4b9u {
  d: path("M6.5 13H12m-5.5 3.75H10");
}

.zgau9oblh {
  cx: 18px;
  cy: 6px;
  r: 3.25px;
}

</style>

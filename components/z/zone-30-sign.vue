<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ugs6g_mvm"/><path class="i6k5rdb9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:zone-30-sign" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i6k5rdb9o {
  d: path("M6.5 7h4.25l-2 3a2.25 2.25 0 1 1-1.5 3.75M15.625 7zA1.875 1.875 0 0 1 17.5 8.875v3.75a1.875 1.875 0 0 1-1.875 1.875a1.875 1.875 0 0 1-1.875-1.875v-3.75A1.875 1.875 0 0 1 15.625 7M7 18h10");
}

.ugs6g_mvm {
  d: path("M7 2.5h10A3.5 3.5 0 0 1 20.5 6v12a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 18V6A3.5 3.5 0 0 1 7 2.5");
}

</style>

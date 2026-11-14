<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e0xlu6znc"/><path class="yf5pu036f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smart-bed" /></template>
<style>
.e0xlu6znc {
  d: path("M3 20.5V6a1.5 1.5 0 0 1 1.5-1.5H7A1.5 1.5 0 0 1 8.5 6v7h11a1.5 1.5 0 0 1 1.5 1.5v3H3m16.5 0v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yf5pu036f {
  d: path("M12.75 10h2a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-2a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5m-7-1.5h.01");
}

</style>

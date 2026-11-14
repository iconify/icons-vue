<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="djza3vh6f"/><path class="kxk9x5bsx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:soda-glass" /></template>
<style>
.djza3vh6f {
  d: path("M7.901 6h8.198a2.625 2.625 0 0 1 2.612 2.886l-.975 9.75A2.625 2.625 0 0 1 15.124 21H8.876a2.625 2.625 0 0 1-2.612-2.364l-.975-9.75A2.625 2.625 0 0 1 7.901 6M15 17.5l3.5-15m-13 6h13");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kxk9x5bsx {
  d: path("M10.25 11.25h1A1.75 1.75 0 0 1 13 13v1a1.75 1.75 0 0 1-1.75 1.75h-1A1.75 1.75 0 0 1 8.5 14v-1a1.75 1.75 0 0 1 1.75-1.75");
}

</style>

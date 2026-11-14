<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lx51vtv2t"/><path class="x28yvx-xb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:video-lock" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lx51vtv2t {
  d: path("M6.875 6h4.25a4.375 4.375 0 0 1 4.375 4.375v3.25A4.375 4.375 0 0 1 11.125 18h-4.25A4.375 4.375 0 0 1 2.5 13.625v-3.25A4.375 4.375 0 0 1 6.875 6");
}

.x28yvx-xb {
  d: path("m16.368 9.994l2.5-1.459a1.75 1.75 0 0 1 2.632 1.512v3.906a1.75 1.75 0 0 1-2.632 1.512l-2.5-1.459a1.75 1.75 0 0 1-.868-1.511v-.99a1.75 1.75 0 0 1 .868-1.511M8.25 11.5h1.5a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75h-1.5a1.75 1.75 0 0 1-1.75-1.75v-.5a1.75 1.75 0 0 1 1.75-1.75m-.75 0v-1a1.5 1.5 0 0 1 3 0v1");
}

</style>

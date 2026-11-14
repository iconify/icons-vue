<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zvi8n84jk"/><path class="r17493b5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:video-upload" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r17493b5k {
  d: path("m16.379 6.6l2.5-1.136A1.5 1.5 0 0 1 21 6.83v3.84a1.5 1.5 0 0 1-2.121 1.366l-2.5-1.136a1.5 1.5 0 0 1-.879-1.366V7.966a1.5 1.5 0 0 1 .879-1.366M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

.zvi8n84jk {
  d: path("M6 3.5h6A3.5 3.5 0 0 1 15.5 7v3.5A3.5 3.5 0 0 1 12 14H6a3.5 3.5 0 0 1-3.5-3.5V7A3.5 3.5 0 0 1 6 3.5");
}

</style>

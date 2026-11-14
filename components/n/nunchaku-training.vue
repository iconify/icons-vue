<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ipks2wbml"/><path class="dri233bjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nunchaku-training" /></template>
<style>
.dri233bjf {
  d: path("M5.5 7.5c0-4.5 6-5.5 6.75-1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ipks2wbml {
  d: path("M5.5 7.5za2 2 0 0 1 2 2v9a2 2 0 0 1-2 2a2 2 0 0 1-2-2v-9a2 2 0 0 1 2-2m6.75-1.629za2 2 0 0 1 2.732.732l4.5 7.794a2 2 0 0 1-.732 2.732a2 2 0 0 1-2.732-.732l-4.5-7.794a2 2 0 0 1 .732-2.732");
}

</style>

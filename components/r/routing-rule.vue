<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="he_0lybyi"/><path class="mg4mvrbnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:routing-rule" /></template>
<style>
.he_0lybyi {
  d: path("m11.561 9.061l1.878 1.878a1.5 1.5 0 0 1 0 2.122l-1.878 1.878a1.5 1.5 0 0 1-2.122 0l-1.878-1.878a1.5 1.5 0 0 1 0-2.122l1.878-1.878a1.5 1.5 0 0 1 2.122 0M2.5 12h4m4-4V5H21M10.5 16v3H21");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mg4mvrbnk {
  d: path("M18.5 2.5L21 5l-2.5 2.5m0 9L21 19l-2.5 2.5");
}

</style>

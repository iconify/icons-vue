<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tve2gfbrx"/><path class="adc6motpy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:stope" /></template>
<style>
.adc6motpy {
  d: path("M9.184 10h5.632a1.5 1.5 0 0 1 1.4 2.038l-1.346 3.5a1.5 1.5 0 0 1-1.4.962h-2.94a1.5 1.5 0 0 1-1.4-.962l-1.346-3.5A1.5 1.5 0 0 1 9.184 10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tve2gfbrx {
  d: path("M2.5 20.5V8L6 5l3 2l4-3.5l4 3l4.5-2v16Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uez0k7bbu"/><path class="upvcfcc5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nurse-call-button" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uez0k7bbu {
  d: path("M11 2.5za5 5 0 0 1 5 5v4a5 5 0 0 1-5 5a5 5 0 0 1-5-5v-4a5 5 0 0 1 5-5");
}

.upvcfcc5j {
  d: path("M8.25 8.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m1.25 4.75h3M11 16.5c0 3 3 3.5 5.5 3c2.25-.5 3.5.25 5 2");
}

</style>

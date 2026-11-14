<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="trtgpubah"/><path class="knuashbqo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:review-resolve" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.knuashbqo {
  d: path("M8.5 11.5L11 14l4.5-4.5");
}

.trtgpubah {
  d: path("M7.75 18.75a8.5 8.5 0 1 0-3-3L3 20.5Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b54s01gew"/><path class="eg-6tgbsa"/><path class="mq-cinv9r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:potty" /></template>
<style>
.b54s01gew {
  d: path("M6 9.25v-4a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v4");
}

.eg-6tgbsa {
  d: path("M4 10.75a8 2.25 0 1 0 16 0a8 2.25 0 1 0-16 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mq-cinv9r {
  d: path("M5 11.75c.5 5 3 6.5 7 6.5s6.5-1.5 7-6.5m-10.25 6.5h6.5a1.25 1.25 0 0 1 1.25 1.25a1.25 1.25 0 0 1-1.25 1.25h-6.5A1.25 1.25 0 0 1 7.5 19.5a1.25 1.25 0 0 1 1.25-1.25");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hzn632b0l"/><path class="xmruo7x8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rod-tube" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hzn632b0l {
  d: path("m4.222 16.243l8.485-8.486a2.5 2.5 0 0 1 3.536 0a2.5 2.5 0 0 1 0 3.536l-8.486 8.485a2.5 2.5 0 0 1-3.535 0a2.5 2.5 0 0 1 0-3.535");
}

.xmruo7x8f {
  d: path("m15.359 4.399l1.06-1.061a1.75 1.75 0 0 1 2.475 0l1.768 1.768a1.75 1.75 0 0 1 0 2.475l-1.061 1.06a1.75 1.75 0 0 1-2.474 0l-1.768-1.768a1.75 1.75 0 0 1 0-2.474");
}

</style>

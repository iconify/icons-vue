<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fusqemdtf"/><path class="ze1vr6qfc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:receipts-stack" /></template>
<style>
.fusqemdtf {
  d: path("M9.25 6h8.5a1.75 1.75 0 0 1 1.75 1.75v11.573a1.036 1.036 0 0 1-1.5.927l-.717-.359a1.75 1.75 0 0 0-1.566 0l-1.434.718a1.75 1.75 0 0 1-1.566 0l-1.434-.718a1.75 1.75 0 0 0-1.566 0L9 20.25a1.036 1.036 0 0 1-1.5-.927V7.75A1.75 1.75 0 0 1 9.25 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ze1vr6qfc {
  d: path("M4.5 17.5V4a1 1 0 0 1 1-1H16m-5.5 7h6m-6 3.5h6");
}

</style>

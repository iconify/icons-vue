<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="adzn-cckj"/><path class="m853-8bsw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:polo-shirt" /></template>
<style>
.adzn-cckj {
  d: path("M7.87 3.73L3.63 6.02q-.88.48-.48 1.4l.95 2.16q.4.92 1.34.57l.12-.05q.94-.35.94.65v9q0 1 1 1h9q1 0 1-1v-9q0-1 .94-.65l.12.05q.94.35 1.34-.57l.95-2.16q.4-.92-.48-1.4l-4.24-2.29q-.88-.48-1.73.04l-1.55.96q-.85.52-1.7 0L9.6 3.77q-.85-.52-1.73-.04");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m853-8bsw {
  d: path("m9.18 3.51l2.39 1.48q.43.26.1.63l-1.34 1.51q-.33.37-.68.02L8.1 5.6q-.35-.35-.13-.8l.56-1.1q.22-.45.65-.19m3.15 2.11l1.34 1.51q.33.37.68.02L15.9 5.6q.35-.35.13-.8l-.56-1.1q-.22-.45-.65-.19l-2.39 1.48q-.43.26-.1.63M12 8v3.5");
}

</style>

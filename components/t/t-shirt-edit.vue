<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g4fc-ijuj"/><path class="gq64eebob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:t-shirt-edit" /></template>
<style>
.g4fc-ijuj {
  d: path("M7.87 3.73L3.63 6.02q-.88.48-.48 1.4l.95 2.16q.4.92 1.34.57l.12-.05q.94-.35.94.65v9q0 1 1 1h9q1 0 1-1v-9q0-1 .94-.65l.12.05q.94.35 1.34-.57l.95-2.16q.4-.92-.48-1.4l-4.24-2.29q-.88-.48-1.88-.48h-4.5q-1 0-1.88.48");
}

.gq64eebob {
  d: path("M9.25 3.5a2.75 2.5 0 0 0 5.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gt3yj4bna"/><path class="dgb2sjblw"/><path class="iqeu88a9k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mention-teammate" /></template>
<style>
.dgb2sjblw {
  d: path("M10 10.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.gt3yj4bna {
  d: path("M5 2.5h14A2.5 2.5 0 0 1 21.5 5v10.5A2.5 2.5 0 0 1 19 18h-8l-4 3.5V18H5a2.5 2.5 0 0 1-2.5-2.5V5A2.5 2.5 0 0 1 5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iqeu88a9k {
  d: path("M14 8.25v3a1.5 1.5 0 0 0 3 0v-1a5 5 0 1 0-1.5 3.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ln5mekb3o"/><path class="pk312p_pd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:signal-edge" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ln5mekb3o {
  fill: currentColor;
  d: path("M4.25 15.5za1.25 1.25 0 0 1 1.25 1.25v2.5a1.25 1.25 0 0 1-1.25 1.25A1.25 1.25 0 0 1 3 19.25v-2.5a1.25 1.25 0 0 1 1.25-1.25m5.25-4za1.25 1.25 0 0 1 1.25 1.25v6.5A1.25 1.25 0 0 1 9.5 20.5a1.25 1.25 0 0 1-1.25-1.25v-6.5A1.25 1.25 0 0 1 9.5 11.5");
}

.pk312p_pd {
  d: path("M14.75 7.5zA1.25 1.25 0 0 1 16 8.75v10.5a1.25 1.25 0 0 1-1.25 1.25a1.25 1.25 0 0 1-1.25-1.25V8.75a1.25 1.25 0 0 1 1.25-1.25m5.25-4za1.25 1.25 0 0 1 1.25 1.25v14.5A1.25 1.25 0 0 1 20 20.5a1.25 1.25 0 0 1-1.25-1.25V4.75A1.25 1.25 0 0 1 20 3.5");
}

</style>

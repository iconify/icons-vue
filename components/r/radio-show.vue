<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qr-51z69n"/><path class="x1k85kprr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:radio-show" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qr-51z69n {
  d: path("M6 8h12a3.5 3.5 0 0 1 3.5 3.5v6A3.5 3.5 0 0 1 18 21H6a3.5 3.5 0 0 1-3.5-3.5v-6A3.5 3.5 0 0 1 6 8m1 0l10.5-5");
}

.x1k85kprr {
  d: path("M12.5 14.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-6.5-2h3m-3 4h3");
}

</style>

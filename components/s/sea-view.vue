<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g4hu_sbay"/><path class="ipv30fb9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sea-view" /></template>
<style>
.g4hu_sbay {
  d: path("M5.625 2.5h12.75A2.625 2.625 0 0 1 21 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 18.875V5.125A2.625 2.625 0 0 1 5.625 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ipv30fb9o {
  d: path("M8.5 11.5a3.5 3.5 0 0 1 7 0Zm-2.5 3q1.5-1.25 3 0t3 0t3 0t3 0M6 18.25q1.5-1.25 3 0t3 0t3 0t3 0");
}

</style>

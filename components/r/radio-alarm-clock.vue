<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rm3ssfbfh"/><path class="ofrt1xqci"/><path class="z2hi2v3lw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:radio-alarm-clock" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ofrt1xqci {
  d: path("M5.5 13.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.rm3ssfbfh {
  d: path("M6 7.5h12a3.5 3.5 0 0 1 3.5 3.5v5.5A3.5 3.5 0 0 1 18 20H6a3.5 3.5 0 0 1-3.5-3.5V11A3.5 3.5 0 0 1 6 7.5m3.5 0a2.5 2.5 0 0 1 5 0");
}

.z2hi2v3lw {
  d: path("M8.5 12.5v1.25h1m5-2.25h4m-4 4h4");
}

</style>

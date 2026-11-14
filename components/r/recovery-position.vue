<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v1pspbaus"/><path class="kz2stkavq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:recovery-position" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kz2stkavq {
  d: path("m9 13.25l-1.5 2.5H3m6.75-2.5l1.5-3.75");
}

.v1pspbaus {
  d: path("M6.75 13.25h6.75l7.5 1.5m-7.5-1.5l3-4l3 3.75m-17 5h19m-19-6.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>

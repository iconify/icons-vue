<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="alavh1bnp"/><path class="f4pcmon4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smart-farm" /></template>
<style>
.alavh1bnp {
  d: path("m2.693 13.158l1.822-3.24a1.5 1.5 0 0 1 .669-.622L8.341 7.81a1.5 1.5 0 0 1 1.31.015l2.938 1.469a1.5 1.5 0 0 1 .636.607l1.832 3.257a1.5 1.5 0 0 1 .193.735V19.5a1.5 1.5 0 0 1-1.5 1.5H4a1.5 1.5 0 0 1-1.5-1.5v-5.607a1.5 1.5 0 0 1 .193-.735");
}

.f4pcmon4m {
  d: path("M8.5 15.75h2a1.5 1.5 0 0 1 1.5 1.5v2.25a1.5 1.5 0 0 1-1.5 1.5h-2A1.5 1.5 0 0 1 7 19.5v-2.25a1.5 1.5 0 0 1 1.5-1.5m6-9.75A3.5 3.5 0 0 1 18 9.5m-3.5-7a7 7 0 0 1 7 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

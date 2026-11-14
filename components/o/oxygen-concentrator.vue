<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jbd5wubbg"/><path class="uuogqtqnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:oxygen-concentrator" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jbd5wubbg {
  d: path("M6.5 6.5h4A3.5 3.5 0 0 1 14 10v6a3.5 3.5 0 0 1-3.5 3.5h-4A3.5 3.5 0 0 1 3 16v-6a3.5 3.5 0 0 1 3.5-3.5m-.5 0v-2c0-1.1.9-2 2-2h1c1.1 0 2 .9 2 2v2");
}

.uuogqtqnc {
  d: path("M5.25 12.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m4.75-.25c0-.75.4-1.25 1-1.25s1 .5 1 1c0 .75-2 1.5-2 2.5h2m-7 7h.01m6.99 0h.01M14 15c3.5 0 4.5-3 4.75-6.5V7M16 4.25c0 2.5 5.5 2.5 5.5 0");
}

</style>

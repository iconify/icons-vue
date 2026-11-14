<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jvdejccij"/><path class="ytk1bobba"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:press-pass" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jvdejccij {
  d: path("M10 5.5v-3h4v3m-5.5 0h7A3.5 3.5 0 0 1 19 9v9a3.5 3.5 0 0 1-3.5 3.5h-7A3.5 3.5 0 0 1 5 18V9a3.5 3.5 0 0 1 3.5-3.5");
}

.ytk1bobba {
  d: path("M9.75 10.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M8.5 16.5h4");
}

</style>

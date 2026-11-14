<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jh868ndmt"/><path class="ccqyc3e8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:x-mark" /></template>
<style>
.ccqyc3e8o {
  d: path("M19.5 4.5q-6 6.5-15 15");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jh868ndmt {
  d: path("M4.5 4.5q6 6.5 15 15");
}

</style>

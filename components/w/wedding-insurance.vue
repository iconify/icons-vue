<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g2py13-0p"/><path class="ivl8kwbsj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wedding-insurance" /></template>
<style>
.g2py13-0p {
  d: path("M4 14.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ivl8kwbsj {
  d: path("M10 14.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0M7.483 5.033l.432-.862A1.21 1.21 0 0 1 9 3.5a1.21 1.21 0 0 1 1.085.671l.432.862a1.5 1.5 0 0 1-.281 1.731L10 7a1.414 1.414 0 0 1-2 0l-.236-.236a1.5 1.5 0 0 1-.281-1.731");
}

</style>

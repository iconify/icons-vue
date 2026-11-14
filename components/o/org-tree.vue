<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="da8znvxxh"/><path class="r1ejtm6oq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:org-tree" /></template>
<style>
.da8znvxxh {
  d: path("M3.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m11 5.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m0 7.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r1ejtm6oq {
  d: path("M6 7.5V16a2 2 0 0 0 2 2h6.5M6 10.25h8.5");
}

</style>

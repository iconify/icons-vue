<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fq6jk4b8t"/><path class="fea7n9bfx"/><path class="div1mjs6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shuffle-2" /></template>
<style>
.div1mjs6h {
  d: path("m18.5 14l3 3l-3 3");
}

.fea7n9bfx {
  d: path("M2.5 7H6c5 0 7 10 12 10h3.5m-3-13l3 3l-3 3");
}

.fq6jk4b8t {
  d: path("M2.5 17H6c5 0 7-10 12-10h3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

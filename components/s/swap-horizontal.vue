<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="seqyflbij"/><path class="abwhqy5wb"/><path class="ok9gfabge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:swap-horizontal" /></template>
<style>
.abwhqy5wb {
  d: path("M16.5 4.5L20 8l-3.5 3.5m3.5 9V16H4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ok9gfabge {
  d: path("M7.5 12.5L4 16l3.5 3.5");
}

.seqyflbij {
  d: path("M4 3.5V8h16");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zgmlzhjgd"/><path class="wwoml4-px"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:monitor-lizard" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wwoml4-px {
  d: path("m9.5 13.25l-1 3.25H7m7.5-3.75l1 3.75H17m2.5-6h1.25l1-1m-1 1l1 1");
}

.zgmlzhjgd {
  d: path("M2.5 11.5L8 10c1.5-1.5 3.5-2 6-2h2.5c1.5 0 2.5 1 3 2.5q-.75 1.5-3 1.5l-1.5.5c-2 1.25-5 1.25-7 0Z");
}

</style>

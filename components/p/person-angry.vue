<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b6q8d6bsy"/><path class="vnd9jo0jo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:person-angry" /></template>
<style>
.b6q8d6bsy {
  d: path("M6.5 8a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0M4 21.5c0-2.5 3.5-5 8-5s8 2.5 8 5M9.25 6.5l1.75 1m3.75-1L13 7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vnd9jo0jo {
  d: path("M10.25 11q1.75-1.25 3.5 0");
}

</style>

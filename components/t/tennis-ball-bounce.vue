<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b28ohdctn"/><path class="h_pvp91wc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tennis-ball-bounce" /></template>
<style>
.b28ohdctn {
  d: path("M6.5 8a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

.h_pvp91wc {
  d: path("M8.25 4c2 2 2 6 0 8m7.5-8c-2 2-2 6 0 8M4 21h16M6.5 15.5L8 17.75m9.5-2.25L16 17.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

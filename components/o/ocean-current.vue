<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vqinnyyzz"/><path class="jff7e60oo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ocean-current" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jff7e60oo {
  d: path("M17.75 3.75L20.5 6.5l-2.75 2.75M2.5 19q3-4.125 6 0t6 0t6 0");
}

.vqinnyyzz {
  d: path("M3.5 13.5c4.5 0 5.5-7 10.5-7h6.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fs1wc6boy"/><path class="xfu7wgbjh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:veteran-player" /></template>
<style>
.fs1wc6boy {
  d: path("M8.25 6.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m-4.75 15C3.5 17 7.25 14 12 14s8.5 3 8.5 7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xfu7wgbjh {
  d: path("m9.5 14.25l2.5 2.5l2.5-2.5m-2.5 2.5a2 2 0 0 1 0 4a2 2 0 0 1 0-4");
}

</style>

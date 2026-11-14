<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eo261bbjr"/><path class="ld6o1i96b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:water-trough-animal" /></template>
<style>
.eo261bbjr {
  d: path("m2.5 5l2 8h12.354m2.732-.343L21.5 5m-15 8v4m7-4v1.9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ld6o1i96b {
  d: path("M3.75 9q2-1 4 0t4 0t4 0t4.5 0m-4 11a2.25 1.5 0 1 0 4.5 0a2.25 1.5 0 1 0-4.5 0m-.5-3.5h.01m2.74-1.25h.01m2.74 1.25h.01");
}

</style>

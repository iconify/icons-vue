<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nrdquht7z"/><path class="eguo6ikph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tram-shelter" /></template>
<style>
.eguo6ikph {
  d: path("M5 14.5h7.5V21m7 0V9m-2.25-2.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nrdquht7z {
  d: path("M5 21V5a1.5 1.5 0 0 1 1.5-1.5h9M2.5 21h19");
}

</style>

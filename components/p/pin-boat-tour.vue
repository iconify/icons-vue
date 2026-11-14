<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ni4rambtz"/><path class="apihy3rtf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-boat-tour" /></template>
<style>
.apihy3rtf {
  d: path("M6.5 8.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M14 18h8l-1.75 3.5h-4.5Zm4 0v-4.5l3.25 4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ni4rambtz {
  d: path("m8.75 19.5l-5-7a6.25 6.25 0 1 1 10 0Z");
}

</style>

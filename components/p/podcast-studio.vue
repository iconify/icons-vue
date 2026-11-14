<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tx6hqy6xp"/><path class="mmeteaccd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:podcast-studio" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mmeteaccd {
  d: path("M6.25 9.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m-1.5 12c0-3.75 1.75-6 4.25-6s4.25 2.25 4.25 6m4-14.5zA1.75 1.75 0 0 1 19 8.75v2.5A1.75 1.75 0 0 1 17.25 13a1.75 1.75 0 0 1-1.75-1.75v-2.5A1.75 1.75 0 0 1 17.25 7m0 6v8.5");
}

.tx6hqy6xp {
  d: path("M2.5 21.5V5A2.5 2.5 0 0 1 5 2.5h14A2.5 2.5 0 0 1 21.5 5v16.5");
}

</style>

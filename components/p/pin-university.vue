<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rpy5h1zny"/><path class="pudody9mo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-university" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pudody9mo {
  d: path("M6.75 11.25v5.25c0 1.5 2.25 3 5.25 3s5.25-1.5 5.25-3v-5.25M21 9.5v6");
}

.rpy5h1zny {
  d: path("m5.872 8.144l5.487-2.592a1.5 1.5 0 0 1 1.282 0l5.487 2.592a1.5 1.5 0 0 1 0 2.712l-5.487 2.592a1.5 1.5 0 0 1-1.282 0l-5.487-2.592a1.5 1.5 0 0 1 0-2.712");
}

</style>

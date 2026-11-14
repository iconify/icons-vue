<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="idoyzpnyj"/><path class="hjkz6acjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smoke-trail" /></template>
<style>
.hjkz6acjs {
  d: path("M14 10c-6 6.5-11 4-9.5 1s6-1 4 3.5c-1.25 2.75-3.5 5-6 6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.idoyzpnyj {
  d: path("m20.005 4.702l-.088.438a1.5 1.5 0 0 1-.41.767l-.3.301a1.5 1.5 0 0 0-.387 1.455l.7 2.567a.86.86 0 0 1-.222.836a.377.377 0 0 1-.596-.084l-.979-1.761a.85.85 0 0 0-1.342-.188l-.285.286a1.5 1.5 0 0 0-.431 1.226l.056.502a.78.78 0 0 1-.224.638a.3.3 0 0 1-.466-.052l-.857-1.347a1.5 1.5 0 0 0-.46-.46l-1.347-.857a.3.3 0 0 1-.052-.466a.78.78 0 0 1 .638-.224l.502.056a1.5 1.5 0 0 0 1.226-.431l.286-.285a.85.85 0 0 0-.188-1.342l-1.761-.979a.377.377 0 0 1-.084-.596a.86.86 0 0 1 .836-.222l2.567.7a1.5 1.5 0 0 0 1.455-.387l.301-.3a1.5 1.5 0 0 1 .767-.41l.438-.088a.6.6 0 0 1 .707.707");
}

</style>

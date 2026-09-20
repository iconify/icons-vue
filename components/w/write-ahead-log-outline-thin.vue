<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="em3t3yypy"/><path class="s2otp9flj"/><path class="p3ntj0cbi"/><path class="mqnae981n"/><path class="kwq9r2piz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:write-ahead-log-outline-thin" /></template>
<style>
.em3t3yypy {
  d: path("M2 5a3 3 0 0 1 3 -3h14a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kwq9r2piz {
  d: path("M2 17a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.mqnae981n {
  d: path("m9 11 3 3 3 -3");
}

.p3ntj0cbi {
  d: path("M15 2v6");
}

.s2otp9flj {
  d: path("M9 2v6");
}

</style>

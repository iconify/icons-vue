<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zli7lqbau"/><path class="fwhv0hbce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shots-on-target" /></template>
<style>
.fwhv0hbce {
  d: path("M13.25 10.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m-6.75 8l5-5m-3.5 0h3.5V17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zli7lqbau {
  d: path("M3 20V7a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v13");
}

</style>

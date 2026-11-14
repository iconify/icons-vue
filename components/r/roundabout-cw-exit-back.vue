<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pfj6r7b0d"/><path class="f0rzsfblj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:roundabout-cw-exit-back" /></template>
<style>
.f0rzsfblj {
  d: path("M12.75 19.25L15 21.5l2.25-2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pfj6r7b0d {
  d: path("M9 21.5V14a5 5 0 1 1 6 0v7.5");
}

</style>

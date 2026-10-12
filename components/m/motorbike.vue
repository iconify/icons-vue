<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="wpd6f3bzf"/><circle class="ekz86bcsq"/><path class="f3zm3obpg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:motorbike" /></template>
<style>
.ekz86bcsq {
  cx: 18.25px;
  cy: 18px;
  r: 3px;
}

.f3zm3obpg {
  d: path("M4 10h3.75q1 0 1.5-.87v-.01q.5-.87 1.5-.87H12q1 0 1.38.92l.99 2.41q.38.92-.62.92H4q-1 0-1-1V11q0-1 1-1m10.25-4H16l1.7 9.05");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wpd6f3bzf {
  cx: 5.75px;
  cy: 18px;
  r: 3px;
}

</style>

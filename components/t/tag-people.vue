<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="aermkxboq"/><path class="xt0lwvbay"/><path class="qnyo8yb5b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tag-people" /></template>
<style>
.aermkxboq {
  cx: 8.5px;
  cy: 6.5px;
  r: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qnyo8yb5b {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.75 6.75h.01");
}

.xt0lwvbay {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 19.75a1 1 0 0 1-1-1a5.75 5.75 0 0 1 11.5 0a1 1 0 0 1-1 1ZM15.5 3.5h2.25q1 0 1.61.79l1.28 1.67q.61.79 0 1.58l-1.28 1.67q-.61.79-1.61.79H15.5q-1 0-1-1V4.5q0-1 1-1");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

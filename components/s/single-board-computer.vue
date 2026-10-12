<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="ofoxgrq4c"/><path class="v8g1hmbbw"/><rect class="cg1u9nj-c"/><path class="p5xe5qgzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:single-board-computer" /></template>
<style>
.cg1u9nj-c {
  width: 5.5px;
  height: 5.5px;
  x: 6.25px;
  y: 11px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.ofoxgrq4c {
  width: 18.5px;
  height: 15.5px;
  x: 2.75px;
  y: 4.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.p5xe5qgzb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.25 12.25h2.5m-2.5 3h2.5");
}

.v8g1hmbbw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 7.5h.01m2.74 0h.01m2.74 0h.01m2.74 0h.01m2.74 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

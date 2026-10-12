<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="wkozi9bqj"/><path class="y4ivzohbm"/><path class="jcttu4brj"/><rect class="qajj1b6yq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oven" /></template>
<style>
.jcttu4brj {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 5.25h.01m3.49 0h.01");
}

.qajj1b6yq {
  width: 10.5px;
  height: 6.75px;
  x: 6.75px;
  y: 11px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.wkozi9bqj {
  width: 17.5px;
  height: 18.5px;
  x: 3.25px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.y4ivzohbm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 7.75h17.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

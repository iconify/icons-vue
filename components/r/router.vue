<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="wjlmhmb_i"/><path class="u7xi22b_k"/><path class="sz6e964qg"/><path class="hbdewjbtf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:router" /></template>
<style>
.hbdewjbtf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.25 16.25h3");
}

.sz6e964qg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 16.25h.01m3.49 0h.01");
}

.u7xi22b_k {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 3.25v9m10.5-9v9");
}

.wjlmhmb_i {
  width: 18.5px;
  height: 8px;
  x: 2.75px;
  y: 12.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

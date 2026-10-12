<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="izyf3bcdo"/><path class="rlq9afbqf"/><path class="h2b8jxb_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nas" /></template>
<style>
.h2b8jxb_a {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.25 18h.01");
}

.izyf3bcdo {
  width: 15.5px;
  height: 18.5px;
  x: 4.25px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.rlq9afbqf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 7.25h8.5m-8.5 3.5h8.5m-8.5 3.5h8.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

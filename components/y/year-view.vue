<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="jlr8ujb1f"/><path class="kwgxelb8x"/><rect class="szm06ac8e"/><path class="jj_a4-j3e"/><rect class="lck3m1bor"/><path class="y4evliqns"/><rect class="xxsqq7bns"/><path class="p2665_k7o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:year-view" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jj_a4-j3e {
  d: path("M13.75 6h7");
}

.jlr8ujb1f {
  width: 7px;
  height: 7px;
  x: 3.25px;
  y: 3.25px;
  rx: 1.75px;
}

.kwgxelb8x {
  d: path("M3.25 6h7");
}

.lck3m1bor {
  width: 7px;
  height: 7px;
  x: 3.25px;
  y: 13.75px;
  rx: 1.75px;
}

.p2665_k7o {
  d: path("M13.75 16.5h7");
}

.szm06ac8e {
  width: 7px;
  height: 7px;
  x: 13.75px;
  y: 3.25px;
  rx: 1.75px;
}

.xxsqq7bns {
  width: 7px;
  height: 7px;
  x: 13.75px;
  y: 13.75px;
  rx: 1.75px;
}

.y4evliqns {
  d: path("M3.25 16.5h7");
}

</style>

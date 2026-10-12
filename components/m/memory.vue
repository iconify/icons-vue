<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="nxsbbobij"/><rect class="yoy-uid8d"/><rect class="b394mbb-w"/><rect class="ea71racey"/><path class="c9mzlu_5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:memory" /></template>
<style>
.b394mbb-w {
  width: 2.5px;
  height: 4.5px;
  x: 10.75px;
  y: 8.25px;
  rx: 0.75px;
}

.c9mzlu_5f {
  d: path("M6.25 15.75v3.5m3.5-3.5v3.5m4.5-3.5v3.5m3.5-3.5v3.5");
}

.ea71racey {
  width: 2.5px;
  height: 4.5px;
  x: 16px;
  y: 8.25px;
  rx: 0.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nxsbbobij {
  width: 18.5px;
  height: 10.5px;
  x: 2.75px;
  y: 5.25px;
  rx: 2px;
}

.yoy-uid8d {
  width: 2.5px;
  height: 4.5px;
  x: 5.5px;
  y: 8.25px;
  rx: 0.75px;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="urfuvbcjk"/><rect class="ve-22ccky"/><rect class="x01a8-d8q"/><path class="zd7hxcctd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:razor" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.urfuvbcjk {
  d: path("M5 2.75h14");
}

.ve-22ccky {
  width: 16.5px;
  height: 3.5px;
  x: 3.75px;
  y: 5px;
  rx: 1.5px;
}

.x01a8-d8q {
  width: 3.5px;
  height: 10.5px;
  x: 10.25px;
  y: 10.75px;
  rx: 1.75px;
}

.zd7hxcctd {
  d: path("M10.25 14.5h3.5m-3.5 2.5h3.5");
}

</style>

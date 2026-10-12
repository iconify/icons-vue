<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="j2ohfp5al"/><path class="zntdm95qk"/><rect class="k2z7vcbvf"/><rect class="use6zmbps"/><path class="r122syeiq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paddle-shifter" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j2ohfp5al {
  cx: 12px;
  cy: 16.25px;
  r: 5px;
}

.k2z7vcbvf {
  width: 6.5px;
  height: 6.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

.r122syeiq {
  d: path("M4.75 6h2.5m9.5 0h2.5M18 4.75v2.5");
}

.use6zmbps {
  width: 6.5px;
  height: 6.5px;
  x: 14.75px;
  y: 2.75px;
  rx: 2px;
}

.zntdm95qk {
  d: path("M7 16h10m-5 0v5.25");
}

</style>

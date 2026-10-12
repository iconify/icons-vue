<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j0z56s0xo"/><circle class="s2oga120n"/><path class="g0jvvobhi"/><circle class="tf2crlbaz"/><path class="b6cxmx1du"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:price-compare" /></template>
<style>
.b6cxmx1du {
  d: path("M16 15.5h3");
}

.g0jvvobhi {
  d: path("M5 13h3m-3 3.5h3m6.46-6.21l2.33-2.33q.71-.71 1.42 0l2.33 2.33q.71.71.71 1.71v8.25q0 1-1 1h-5.5q-1 0-1-1V12q0-1 .71-1.71");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j0z56s0xo {
  d: path("m3.46 7.29l2.33-2.33q.71-.71 1.42 0l2.33 2.33q.71.71.71 1.71v11.25q0 1-1 1h-5.5q-1 0-1-1V9q0-1 .71-1.71");
}

.s2oga120n {
  cx: 6.5px;
  cy: 8.25px;
  r: 1px;
}

.tf2crlbaz {
  cx: 17.5px;
  cy: 11.25px;
  r: 1px;
}

</style>

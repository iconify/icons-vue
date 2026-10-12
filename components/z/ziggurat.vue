<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mz038dbaz"/><rect class="a_d4dkbnk"/><path class="n-az8eiwh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ziggurat" /></template>
<style>
.a_d4dkbnk {
  width: 3.5px;
  height: 11.75px;
  x: 10.25px;
  y: 9.5px;
  rx: 0.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mz038dbaz {
  d: path("M2.75 20.75V17.5q0-.5.5-.5H4.5q.5 0 .5-.5v-3.25q0-.5.5-.5H7q.5 0 .5-.5V9q0-.5.5-.5h1.25q.5 0 .5-.5V5q0-.5.5-.5h3.5q.5 0 .5.5v3q0 .5.5.5H16q.5 0 .5.5v3.25q0 .5.5.5h1.5q.5 0 .5.5v3.25q0 .5.5.5h1.25q.5 0 .5.5v3.25q0 .5-.5.5H3.25q-.5 0-.5-.5");
}

.n-az8eiwh {
  d: path("M10.25 13h3.5m-3.5 3.75h3.5");
}

</style>

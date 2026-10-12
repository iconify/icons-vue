<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="mmkci1s_q"/><rect class="uo-znoxiv"/><path class="ro1pudbnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:radar-marine" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mmkci1s_q {
  width: 17.5px;
  height: 2.25px;
  x: 3.25px;
  y: 6px;
  rx: 1.1px;
}

.ro1pudbnu {
  d: path("M12 12v7.75m-3.5.75h7m1.94-10.86A6 6 0 0 1 15 12.3m4.99-2.29a8.5 8.5 0 0 1-3.11 4.05");
}

.uo-znoxiv {
  width: 4px;
  height: 3.75px;
  x: 10px;
  y: 8.25px;
  rx: 0.75px;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fz6_qeonv"/><rect class="bvvf3jt6i"/><path class="tuee6itcy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rain-gauge" /></template>
<style>
.bvvf3jt6i {
  width: 9px;
  height: 14.75px;
  x: 7.5px;
  y: 6.5px;
  rx: 1.5px;
}

.fz6_qeonv {
  d: path("M5.1 2.75h13.8q.6 0 .23.47l-2.26 2.81q-.37.47-.97.47H8.1q-.6 0-.97-.47L4.87 3.22q-.37-.47.23-.47");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tuee6itcy {
  d: path("M7.5 10.75h3m-3 4.75q2.25-2 4.5 0t4.5 0");
}

</style>

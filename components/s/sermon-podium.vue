<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q12barb4j"/><rect class="ma04geecb"/><path class="uxzom64zc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sermon-podium" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ma04geecb {
  width: 7.5px;
  height: 7.5px;
  x: 8.25px;
  y: 11.25px;
  rx: 1.25px;
}

.q12barb4j {
  d: path("m4.34 6.13l15.32-3.26q.59-.12.59.48v2.8q0 .6-.59.68L4.34 8.92q-.59.08-.59-.52V6.85q0-.6.59-.72M12 7.88v3.37m0 7.5v2.5m-5 0h10");
}

.uxzom64zc {
  d: path("M12 13.75v2.5m-1-1.5h2");
}

</style>

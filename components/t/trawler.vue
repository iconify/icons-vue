<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n7kiytbfs"/><rect class="y48667bfd"/><path class="kvx15pbnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trawler" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kvx15pbnj {
  d: path("M14.5 14.5V4m0 0c3.5 1.25 6.25 3.5 6.5 7.5");
}

.n7kiytbfs {
  d: path("M3.5 14.5h17q.75 0 .39.66l-2.03 3.68q-.36.66-1.11.66h-12q-.75 0-1.06-.68l-1.63-3.64q-.31-.68.44-.68");
}

.y48667bfd {
  width: 5.5px;
  height: 4.5px;
  x: 5.75px;
  y: 10px;
  rx: 0.75px;
}

</style>

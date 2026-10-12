<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wdd_k9f2l"/><path class="udp07fmnq"/><path class="g9zld1hdf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paper-recycle" /></template>
<style>
.g9zld1hdf {
  d: path("M12.5 7v2.75h2.75M10.5 12.5h3m-3 2.5h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.udp07fmnq {
  d: path("M9.25 6.75h2.5q1 0 1.71.71l1.58 1.58q.71.71.71 1.71v5.5q0 1-1 1h-5.5q-1 0-1-1v-8.5q0-1 1-1");
}

.wdd_k9f2l {
  d: path("M16.5 4.21a9 9 0 1 1-9 0m-.65 2.42l.65-2.42l-2.42-.65");
}

</style>

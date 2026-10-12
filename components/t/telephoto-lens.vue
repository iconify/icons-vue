<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qjxcpf2qw"/><path class="lfqa0jb_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:telephoto-lens" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lfqa0jb_j {
  d: path("M10.25 13.25h1q.75 0 .75.75v2.75q0 .75.75.75h1q.75 0 .75.75v1q0 .75-.75.75h-6Q7 20 7 19.25v-1q0-.75.75-.75h1q.75 0 .75-.75V14q0-.75.75-.75");
}

.qjxcpf2qw {
  d: path("M4 6.75h10q1.25 0 1.25-1t1.25-1H20q1.25 0 1.25 1.25v8q0 1.25-1.25 1.25h-3.5q-1.25 0-1.25-1t-1.25-1H4q-1.25 0-1.25-1.25V8q0-1.25 1.25-1.25m1 0v6.5m2.5-6.5v6.5");
}

</style>

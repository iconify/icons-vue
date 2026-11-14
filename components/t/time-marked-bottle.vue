<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a1ky85bfs"/><path class="zae5yzbjd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:time-marked-bottle" /></template>
<style>
.a1ky85bfs {
  d: path("M9 7.5v1q-2 1-2 3.5v8q0 1.5 1.5 1.5h7q1.5 0 1.5-1.5v-8q0-2.5-2-3.5v-1m-5-3h4A1.5 1.5 0 0 1 15.5 6A1.5 1.5 0 0 1 14 7.5h-4A1.5 1.5 0 0 1 8.5 6A1.5 1.5 0 0 1 10 4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zae5yzbjd {
  d: path("M12 6.5a2 2 0 0 1 0-4M10 12h3m-3 3h2m-2 3h3");
}

</style>

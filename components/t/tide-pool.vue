<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hnkjtmxqu"/><path class="yaq2vkkth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tide-pool" /></template>
<style>
.hnkjtmxqu {
  d: path("M3.88 11.25zQ5 8.5 7.85 7.55l.3-.1q2.85-.95 5.83-.61l.54.07q2.98.34 4.72 2.78l.27.37q1.74 2.44 1.15 5.38l-.07.37q-.59 2.94-3.42 3.95l-1.34.48q-2.83 1.01-5.77.42l-1.62-.32q-2.94-.59-4.23-3.3l-.17-.33Q2.75 14 3.88 11.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yaq2vkkth {
  d: path("m12.15 10.82l.76 1.66q.15.31.5.35l1.81.22q.35.04.09.28l-1.34 1.24q-.26.24-.19.58l.36 1.79q.06.34-.24.17l-1.59-.89q-.31-.17-.62 0l-1.59.89q-.3.17-.24-.17l.36-1.79q.07-.34-.19-.58l-1.34-1.24q-.26-.24.09-.28l1.81-.22q.35-.04.5-.35l.76-1.66q.15-.32.3 0");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pw78r0b-i"/><path class="v0h4e9q2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pitcher" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pw78r0b-i {
  d: path("M2.75 3.75h12.5v6.75c0 1.5 1 2 1 4.25a6.5 6.5 0 0 1-6.5 6.5a6.5 6.5 0 0 1-6.5-6.5c0-3.5 2-4.75 2-6.25c0-2-1-3.25-2.5-4.75");
}

.v0h4e9q2g {
  d: path("M15.25 5H18a2 2 0 0 1 2 2v1.5a2 2 0 0 1-2 2h-2.75M6 14.5q1.875-1.125 3.75 0c1.875 1.125 2.5.75 3.75 0");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="od2u69bvl"/><path class="yaomqcgzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:welcome-mat" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.od2u69bvl {
  d: path("M5.25 11.5V4.75a2 2 0 0 1 2-2h9.5a2 2 0 0 1 2 2v6.75m-10.5 1.75h7.5q1.5 0 2.17 1.34l2.16 4.32q.67 1.34-.83 1.34H4.75q-1.5 0-.83-1.34l2.16-4.32q.67-1.34 2.17-1.34");
}

.yaomqcgzt {
  d: path("M8.25 16.75q1.125-1.875 2.25 0c1.125 1.875 1.5 1.25 2.25 0s1.5-1.25 2.25 0");
}

</style>

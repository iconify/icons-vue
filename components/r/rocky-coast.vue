<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wiidd9fkt"/><path class="jzxu2jn8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rocky-coast" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jzxu2jn8y {
  d: path("M2.5 21q2.5-2 5 0t5 0t5 0t4 0");
}

.wiidd9fkt {
  d: path("m2.924 11.663l.965-4.182a1.5 1.5 0 0 1 .485-.802l1.748-1.498a1.5 1.5 0 0 1 2.278.395l.1.174a1.205 1.205 0 0 0 2.068.041l.182-.291a1.38 1.38 0 0 1 2.379.071l1.73 3.17a1.5 1.5 0 0 1 .174.552l.282 2.541a1.5 1.5 0 0 1-1.491 1.666H4.386a1.5 1.5 0 0 1-1.462-1.837M2.5 17.5q2.5-2 5 0t5 0t5 0t4 0");
}

</style>

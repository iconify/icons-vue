<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hufav1q4n"/><path class="cq8pmsb0m"/><path class="illa3qtwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:orbit-camera" /></template>
<style>
.cq8pmsb0m {
  d: path("m7 8.25l4 2.25l4-2.25m-4 2.25V15m-8.5-1.5a8.5 5 0 0 0 17 0v-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hufav1q4n {
  d: path("m11.735 6.414l2.5 1.406A1.5 1.5 0 0 1 15 9.127v2.746a1.5 1.5 0 0 1-.765 1.307l-2.5 1.406a1.5 1.5 0 0 1-1.47 0l-2.5-1.406A1.5 1.5 0 0 1 7 11.873V9.127a1.5 1.5 0 0 1 .765-1.307l2.5-1.406a1.5 1.5 0 0 1 1.47 0");
}

.illa3qtwa {
  d: path("m17.75 13.25l1.75-1.75l1.75 1.75");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="anwdzrbsn"/><path class="yqppunb1q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:warning-drop" /></template>
<style>
.anwdzrbsn {
  d: path("m14.301 6.939l5.313 9.672a2.625 2.625 0 0 1-2.301 3.889H6.687a2.625 2.625 0 0 1-2.301-3.889l5.313-9.672a2.625 2.625 0 0 1 4.602 0M12 9v7.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yqppunb1q {
  d: path("m9.5 13.75l2.5 2.5l2.5-2.5");
}

</style>

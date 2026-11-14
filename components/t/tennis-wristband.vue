<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="spjyovp4g"/><path class="emx5mackx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tennis-wristband" /></template>
<style>
.emx5mackx {
  d: path("M3 11.5q9 3 18 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.spjyovp4g {
  d: path("M3 7q9 3 18 0v9q-9 3-18 0Z");
}

</style>

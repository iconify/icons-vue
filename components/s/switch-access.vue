<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f0z242bas"/><path class="c3-6o8b5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:switch-access" /></template>
<style>
.c3-6o8b5t {
  d: path("M2.75 14a9.25 4 0 0 0 18.5 0M12 2.75v6.5m-2.5-2.5l2.5 2.5l2.5-2.5");
}

.f0z242bas {
  d: path("M2.75 14a9.25 4 0 0 1 18.5 0v3.25a9.25 4 0 0 1-18.5 0Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

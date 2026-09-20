<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fozhwebbv"/><path class="uzmclv6tb"/><path class="m3ubefbgj"/><path class="z55just5o"/><path class="qjx5s3xna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:service-k8s-outline-thin" /></template>
<style>
.fozhwebbv {
  d: path("M10 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m3ubefbgj {
  d: path("M3 13a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.qjx5s3xna {
  d: path("M15 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.uzmclv6tb {
  d: path("M12 8v3");
}

.z55just5o {
  d: path("M7 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>

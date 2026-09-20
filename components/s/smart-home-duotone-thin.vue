<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m_g_lvb6y"/><path class="gkvem8baj"/><path class="p6ibjbc2t"/><path class="fqjbkn2kp"/><path class="it8-m-z-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:smart-home-duotone-thin" /></template>
<style>
.fqjbkn2kp {
  d: path("M8 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.gkvem8baj {
  fill: currentColor;
  d: path("M8 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.it8-m-z-e {
  d: path("M19 9c2 3 2 7 0 10");
}

.m_g_lvb6y {
  fill: currentColor;
  d: path("M3 20v-8l7 -7 7 7v8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.p6ibjbc2t {
  d: path("M3 20v-8l7 -7 7 7v8Z");
}

</style>

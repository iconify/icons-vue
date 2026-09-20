<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jof7c9fpk"/><path class="ldq326b0y"/><path class="m-p3hbclp"/><path class="vu9j-xb3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:settings-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jof7c9fpk {
  d: path("M4 9h16");
}

.ldq326b0y {
  d: path("M9 7v4");
}

.m-p3hbclp {
  d: path("M4 15h16");
}

.vu9j-xb3y {
  d: path("M15 13v4");
}

</style>

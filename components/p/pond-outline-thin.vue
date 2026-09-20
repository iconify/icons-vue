<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b-af79bpy"/><path class="hk8a83bva"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pond-outline-thin" /></template>
<style>
.b-af79bpy {
  d: path("M12 7c5 0 9 2 9 6s-4 6 -9 6 -9 -2 -9 -6 4 -6 9 -6");
}

.hk8a83bva {
  d: path("M8 15c2 -2 6 -2 8 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

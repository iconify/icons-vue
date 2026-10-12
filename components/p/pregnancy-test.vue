<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="jtzp7rbiy"/><rect class="m9nmsyb5h"/><path class="uglg8-way"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pregnancy-test" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jtzp7rbiy {
  width: 10px;
  height: 18.5px;
  x: 7px;
  y: 2.75px;
  rx: 5px;
}

.m9nmsyb5h {
  width: 5px;
  height: 6.5px;
  x: 9.5px;
  y: 7.5px;
  rx: 1px;
}

.uglg8-way {
  d: path("M12 9.25v3M7 16.5h10");
}

</style>

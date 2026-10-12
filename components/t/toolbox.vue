<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="z-t91k_tz"/><path class="ttf49obnu"/><rect class="a4ef03r1r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:toolbox" /></template>
<style>
.a4ef03r1r {
  width: 3.5px;
  height: 3.5px;
  x: 10.25px;
  y: 11.25px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ttf49obnu {
  d: path("M8.5 8.25v-2a1.5 1.5 0 0 1 1.5-1.5h4a1.5 1.5 0 0 1 1.5 1.5v2M2.75 13h7.5m3.5 0h7.5");
}

.z-t91k_tz {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 8.25px;
  rx: 2px;
}

</style>

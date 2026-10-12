<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tkwhs4bzs"/><rect class="ykm1yvbdz"/><path class="ktmoa1bkz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sandbox-box" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ktmoa1bkz {
  d: path("M9.25 8.5h-2m7.5 0h2m-7.5 3h-2m7.5 0h2M10.5 5l-.75-1.5M13.5 5l.75-1.5");
}

.tkwhs4bzs {
  d: path("M2.75 9v10A2.25 2.25 0 0 0 5 21.25h14A2.25 2.25 0 0 0 21.25 19V9m-18.5 9.25c3-1.25 6-1.75 9.25-1.75s6.25.5 9.25 1.75");
}

.ykm1yvbdz {
  width: 5.5px;
  height: 9px;
  x: 9.25px;
  y: 5px;
  rx: 2.75px;
}

</style>

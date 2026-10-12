<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="k54q1_x4v"/><path class="p9ltdabyn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:slide-ai" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k54q1_x4v {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 3.25px;
  rx: 2.25px;
}

.p9ltdabyn {
  d: path("M12 15.75v2.5m-3.5 3l3.5-3l3.5 3M12 5.75q.45 3.3 3.75 3.75q-3.3.45-3.75 3.75q-.45-3.3-3.75-3.75q3.3-.45 3.75-3.75");
}

</style>

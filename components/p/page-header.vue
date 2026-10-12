<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="wuln3c1ei"/><path class="q9g_46b7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:page-header" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q9g_46b7e {
  d: path("M3.75 9.75v9.5a2 2 0 0 0 2 2h12.5a2 2 0 0 0 2-2v-9.5M7.5 13.5h9m-9 3.5h6");
}

.wuln3c1ei {
  width: 16.5px;
  height: 4.75px;
  x: 3.75px;
  y: 2.75px;
  rx: 1.75px;
}

</style>

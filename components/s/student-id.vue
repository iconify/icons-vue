<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dnp2npbye"/><path class="ih46qg1sx"/><path class="t--6k3bfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:student-id" /></template>
<style>
.dnp2npbye {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ih46qg1sx {
  d: path("M10.25 5.75h3.5m-1.3 2.47l3.1 1.56q.45.22 0 .44l-3.1 1.56q-.45.22-.9 0l-3.1-1.56q-.45-.22 0-.44l3.1-1.56q.45-.22.9 0");
}

.t--6k3bfo {
  d: path("M9.75 10.88v2.62q2.25 1.5 4.5 0v-2.62M8.5 18h7");
}

</style>

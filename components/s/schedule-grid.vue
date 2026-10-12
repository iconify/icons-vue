<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="luxaszu4f"/><path class="in-bmtbvw"/><rect class="ltorydrde"/><rect class="scutd-z5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:schedule-grid" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.in-bmtbvw {
  d: path("M3.25 8.25h17.5m-12.5 0v12.5m-3-8.75h1m-1 5h1");
}

.ltorydrde {
  width: 7px;
  height: 2.5px;
  x: 10.75px;
  y: 10.75px;
  rx: 1.25px;
}

.luxaszu4f {
  width: 17.5px;
  height: 17.5px;
  x: 3.25px;
  y: 3.25px;
  rx: 2.5px;
}

.scutd-z5i {
  width: 4.5px;
  height: 2.5px;
  x: 10.75px;
  y: 15.75px;
  rx: 1.25px;
}

</style>

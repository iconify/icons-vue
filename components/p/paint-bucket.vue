<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ftngk-bfo"/><path class="adi5spb0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paint-bucket" /></template>
<style>
.adi5spb0a {
  d: path("M5.25 9C5.25 5.5 7 3.25 9.5 3.25S13.75 5.5 13.75 9m-10 3.5h11.5m4.5-.5c.8 1 1.5 2 1.5 2.9a1.5 1.5 0 0 1-3 0c0-.9.7-1.9 1.5-2.9");
}

.ftngk-bfo {
  width: 11.5px;
  height: 12.25px;
  x: 3.75px;
  y: 9px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

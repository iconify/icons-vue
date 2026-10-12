<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ucxu3gbut"/><rect class="s6zixlb9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:picture-in-picture-off" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s6zixlb9z {
  width: 5.5px;
  height: 4.25px;
  x: 12.25px;
  y: 11.75px;
  rx: 1px;
}

.ucxu3gbut {
  width: 18.5px;
  height: 14.5px;
  x: 2.75px;
  y: 4.75px;
  rx: 2.5px;
}

</style>

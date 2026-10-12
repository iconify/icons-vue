<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="psrh26ros"/><rect class="bwvftibxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pause" /></template>
<style>
.bwvftibxc {
  width: 4.5px;
  height: 16.5px;
  x: 13.75px;
  y: 3.75px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.psrh26ros {
  width: 4.5px;
  height: 16.5px;
  x: 5.75px;
  y: 3.75px;
  rx: 1.5px;
}

</style>

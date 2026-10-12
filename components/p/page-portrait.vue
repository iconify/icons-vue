<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="zah1fx37a"/><rect class="img0046lo"/><path class="u9ifsz1za"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:page-portrait" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.img0046lo {
  width: 8.5px;
  height: 6.25px;
  x: 12.75px;
  y: 15px;
  rx: 1.5px;
}

.u9ifsz1za {
  d: path("M11.75 4h2a5 5 0 0 1 5 5v2.25M16.5 9l2.25 2.25L21 9");
}

.zah1fx37a {
  width: 7.25px;
  height: 12.5px;
  x: 2.75px;
  y: 8.75px;
  rx: 1.5px;
}

</style>

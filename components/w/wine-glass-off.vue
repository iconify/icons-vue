<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ynh8u9bns"/><path class="oryd3cclm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wine-glass-off" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oryd3cclm {
  d: path("M9 8.25h6a3 3 0 0 1-6 0m3 5.25v7.75m-3.5 0h7");
}

.ynh8u9bns {
  d: path("M6.75 2.75h10.5c.65 1.5 1 3 1 4.5a6.25 6.25 0 0 1-12.5 0c0-1.5.35-3 1-4.5");
}

</style>

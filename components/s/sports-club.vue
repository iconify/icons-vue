<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lbrqr8yam"/><path class="lxhoymbab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sports-club" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lbrqr8yam {
  d: path("M3.5 14.5L12 8l8.5 6.5v7h-17ZM12 8V2.5m1.437.431l1.063.319a.783.783 0 0 1 0 1.5l-1.063.319A1.116 1.116 0 0 1 12 4a1.116 1.116 0 0 1 1.437-1.069");
}

.lxhoymbab {
  d: path("M10 21.5v-4h4v4");
}

</style>

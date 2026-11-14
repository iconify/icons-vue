<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="t_84qr0xw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:public-domain" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oy9aotbsd {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

.t_84qr0xw {
  d: path("M10.875 11h2.25a2.625 2.625 0 0 1 2.625 2.625v.75A2.625 2.625 0 0 1 13.125 17h-2.25a2.625 2.625 0 0 1-2.625-2.625v-.75A2.625 2.625 0 0 1 10.875 11M10 11V7.5a2 2 0 0 1 4 0");
}

</style>

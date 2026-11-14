<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l62zclblf"/><path class="u61k-xbtj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:outdoor-shower" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l62zclblf {
  d: path("M6 21V6a2.5 2.5 0 0 1 2.5-2.5H11a2 2 0 0 1 2 2");
}

.u61k-xbtj {
  d: path("M10 8.5a3 3 0 0 1 6 0ZM3 21h6m2-9h.01M15 12h.01M13 15h.01M12 21h9");
}

</style>

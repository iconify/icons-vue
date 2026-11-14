<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fj3aoy5co"/><path class="z6fzfac5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:robot-vacuum-return" /></template>
<style>
.fj3aoy5co {
  d: path("M10 8a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0M4.25 18h6.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75h-6.5a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 4.25 18M15.5 8h.01m3.99 8.25a3.5 3.5 0 0 1-3.5 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z6fzfac5j {
  d: path("m18 17.75l-2 2l2 2");
}

</style>

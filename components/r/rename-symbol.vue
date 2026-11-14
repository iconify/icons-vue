<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lyf1cr_6c"/><path class="eneh5abtm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rename-symbol" /></template>
<style>
.eneh5abtm {
  d: path("M13 3v5h5m-7.5 13h-5c-.83 0-1.5-.67-1.5-1.5v-15M14.75 22l.5-2.5L20 14.75l2 2l-4.75 4.75Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lyf1cr_6c {
  d: path("M4 4.5C4 3.67 4.67 3 5.5 3H13l5 5v4.5");
}

</style>

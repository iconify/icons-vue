<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iu56fabsd"/><path class="snftfcbto"/><path class="b69cm1qkb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:subscript-line-duotone" /></template>
<style>
.b69cm1qkb {
  d: path("M13.5 2L3 16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iu56fabsd {
  d: path("M17 16.8461C17 15.8265 17.8954 15 19 15C20.1046 15 21 15.8265 21 16.8461C21 17.8656 20.5634 18.356 19.7915 19.257L17 22H21");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.snftfcbto {
  d: path("M3 2L13.5 16");
}

</style>

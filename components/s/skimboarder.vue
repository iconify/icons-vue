<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jenr3ybjg"/><path class="bkt517b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:skimboarder" /></template>
<style>
.bkt517b4s {
  d: path("M12 6.5V14l-4 5.5m4-5.5l4 5.5m-13 0h18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jenr3ybjg {
  d: path("M10 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-6.5 5h17");
}

</style>

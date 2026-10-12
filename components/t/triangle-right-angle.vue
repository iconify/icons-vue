<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ofyfpwwjf"/><path class="zxsa6nb8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:triangle-right-angle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ofyfpwwjf {
  d: path("M4.5 20.25h15q1.5 0 .59-1.19L9.41 5.19Q8.5 4 8.02 5.42L3.48 18.83Q3 20.25 4.5 20.25");
}

.zxsa6nb8l {
  d: path("M8.5 20.25a5.5 5.5 0 0 0-3.74-5.21");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x7wnkebki"/><path class="giyq9xavu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:overtime" /></template>
<style>
.giyq9xavu {
  d: path("M9.5 10.5v4l3 1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x7wnkebki {
  d: path("M18.804 11.455A3.8 3.8 0 0 0 20.25 11C17.5 10.25 16 6.25 16.5 2.75c-1.405.422-2.336 1.554-2.661 2.908M2.5 14.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0");
}

</style>

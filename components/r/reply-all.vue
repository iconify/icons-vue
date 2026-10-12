<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fdmk6kshg"/><path class="ayd36ibye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reply-all" /></template>
<style>
.ayd36ibye {
  d: path("M8.5 10.5h5.75a6 6 0 0 1 6 6v2");
}

.fdmk6kshg {
  d: path("M8 6.25L3.75 10.5L8 14.75m4.75-8.5L8.5 10.5l4.25 4.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

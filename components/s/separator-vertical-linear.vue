<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rb-l41-ka"/><path class="jrvuve-_c"/><path class="x1f4lc3zb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:separator-vertical-linear" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jrvuve-_c {
  d: path("M15 18L21 12L15 6");
}

.rb-l41-ka {
  d: path("M9 18L3 12L9 6");
}

.x1f4lc3zb {
  d: path("M12 2L12 22");
}

</style>

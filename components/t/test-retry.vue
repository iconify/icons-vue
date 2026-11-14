<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jks-j8nup"/><path class="zpb_sxbkz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:test-retry" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jks-j8nup {
  d: path("M20 12a8 8 0 1 1-2.25-5.75");
}

.zpb_sxbkz {
  d: path("M17.75 2.5v3.75H14");
}

</style>

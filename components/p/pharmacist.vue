<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zied-1bie"/><path class="xp-lx4bvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pharmacist" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xp-lx4bvl {
  d: path("M8.75 14.5L11 18l2.25-3.5m4.25-.5h2a1.25 1.25 0 0 1 1.25 1.25a1.25 1.25 0 0 1-1.25 1.25h-2a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 17.5 14m-.75 2.5h3a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 19.75 22h-3A1.75 1.75 0 0 1 15 20.25v-2a1.75 1.75 0 0 1 1.75-1.75");
}

.zied-1bie {
  d: path("M7 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m-3.5 14v-2c0-3 3.5-5.25 7.5-5.25c.853 0 1.684.102 2.463.293");
}

</style>

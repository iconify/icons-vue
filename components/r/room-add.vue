<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wpmts-2_i"/><path class="rsqbw-b4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:room-add" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rsqbw-b4i {
  d: path("M5 19a5 5 0 0 1 5-5m8 1v6m-3-3h6");
}

.wpmts-2_i {
  d: path("M10 19h2.4m6.6-6.6V2.5H2.5V19H5m5 0v-5");
}

</style>

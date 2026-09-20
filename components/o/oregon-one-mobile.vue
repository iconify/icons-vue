<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="f_v_dfbgn"/><path class="o3n8kbbii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oregon-one-mobile" /></template>
<style>
.f_v_dfbgn {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
}

.o3n8kbbii {
  d: path("M8.669 22.61a4.276 4.276 0 1 1 8.551 0v2.78a4.276 4.276 0 1 1-8.551 0zm19.607 7.055V22.61a4.276 4.276 0 1 0-8.551 0m-.001 7.055v-11.33m19.046 9.173a4.276 4.276 0 0 1-7.99-2.118v-2.78a4.276 4.276 0 1 1 8.551 0V24H30.78");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

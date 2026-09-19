<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="hp1l-_bsw"/><path class="c9x-2ib8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:raag" /></template>
<style>
.c9x-2ib8w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.185 36.956V4.5s13.009 5.782 7.542 22.015");
}

.hp1l-_bsw {
  cx: 19.558px;
  cy: 36.956px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.627px;
  ry: 6.544px;
}

</style>

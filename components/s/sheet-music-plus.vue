<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gv7r76b5a"/><circle class="wlo8rlbpx"/><path class="ss4imzden"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sheet-music-plus" /></template>
<style>
.gv7r76b5a {
  d: path("M4 7h7.25m4.5 0H20M4 12h2.67m9.83 0H20M4 17h2.67m8.66 0H20");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ss4imzden {
  d: path("M13.5 14.5v-9");
}

.wlo8rlbpx {
  cx: 11px;
  cy: 14.5px;
  r: 2.5px;
}

</style>

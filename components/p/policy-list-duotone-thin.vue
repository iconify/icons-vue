<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wuq55s4_w"/><path class="ga97lpb2d"/><path class="g_14gdcpn"/><path class="u83rpxb8q"/><path class="pdgwdvrql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:policy-list-duotone-thin" /></template>
<style>
.g_14gdcpn {
  d: path("M15 9h7");
}

.ga97lpb2d {
  d: path("M3 5h9v6l-4.5 4.5L3 11Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pdgwdvrql {
  d: path("M15 17h7");
}

.u83rpxb8q {
  d: path("M15 13h7");
}

.wuq55s4_w {
  fill: currentColor;
  d: path("M3 5h9v6l-4.5 4.5L3 11Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h8uaxgswm"/><path class="c7dgfu7wx"/><path class="qynh2c4wy"/><path class="cwwg2gv6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:object-store-outline-thin" /></template>
<style>
.c7dgfu7wx {
  d: path("M2 4h20");
}

.cwwg2gv6o {
  d: path("M13 13a2 2 0 0 1 2 -2 2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2Z");
}

.h8uaxgswm {
  d: path("M4 8v12h16V8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qynh2c4wy {
  d: path("M7 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>

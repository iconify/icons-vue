<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="tgj7e0bzn"/><path class="t9wugacul"/><path class="me5kafbop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tag-person-sharp" /></template>
<style>
.me5kafbop {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.5 11.75h.01");
}

.t9wugacul {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 20.25h10.75v-.75c0-3-2.6-5.25-5.75-5.25S2.75 16.5 2.75 19.5v.75zm14-12h3.75v7H17.5l-2.5-3.5Z");
}

.tgj7e0bzn {
  cx: 8.5px;
  cy: 7.75px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

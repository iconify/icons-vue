<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ihp0adchw"/><path class="vk6l63buw"/><circle class="zofk-exqs"/><circle class="jz58izt2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ride-share-sharp" /></template>
<style>
.ihp0adchw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.24 13.35l1.27-2.95L5 9.25h14l.49 1.15l1.27 2.95l.49 1.15V19H2.75v-4.5zM5.5 19v2.25m13-2.25v2.25");
}

.jz58izt2b {
  cx: 15px;
  cy: 4.75px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vk6l63buw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.25 15h.01m11.49 0h.01");
}

.zofk-exqs {
  cx: 9px;
  cy: 4.75px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="uk3ry_1ge"/><circle class="gzk5d2xwl"/><path class="x1jpzin5b"/><path class="ham-4mshf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tea-infuser-sharp" /></template>
<style>
.gzk5d2xwl {
  cx: 12px;
  cy: 15.25px;
  r: 6px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ham-4mshf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 18.25h.01m3.49 0h.01");
}

.uk3ry_1ge {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3h4v3.5h-4zm2 3.5v2.75");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.x1jpzin5b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 15.25h12");
}

</style>

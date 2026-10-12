<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="vcvako1fj"/><path class="ya0otcbgd"/><path class="qcpfwcbkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sindhi-topi-sharp" /></template>
<style>
.qcpfwcbkw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 14h.01M17 14h.01M7 17h.01M17 17h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vcvako1fj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8.5c0-1.25 3.4-2.25 7.5-2.25s7.5 1 7.5 2.25v10.75h-5V15.5a2.5 2.5 0 0 0-5 0v3.75h-5V18Z");
}

.ya0otcbgd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8.5c0 1.25 3.4 2.25 7.5 2.25s7.5-1 7.5-2.25");
}

</style>

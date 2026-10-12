<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="c6kx5ybwj"/><path class="s9uyqacfh"/><path class="foqzl0b5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nightstand-sharp" /></template>
<style>
.c6kx5ybwj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 2.75h2.75l.25.71l1.25 3.58l.25.71h-7l.25-.71L10 3.46l.25-.71zm1 5V11m-7.25.75h14.5v8H4.75zm0 4h14.5");
}

.foqzl0b5k {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 19.75v1.5m10-1.5v1.5");
}

.s9uyqacfh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 13.75h.01m-.01 4h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

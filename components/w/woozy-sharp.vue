<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="nzuju3bua"/><path class="d0cx5wqfm"/><path class="qwojw7b6x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:woozy-sharp" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.d0cx5wqfm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 10.5h.01");
}

.nzuju3bua {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 9.25l1.375 1.1l1.375-1.1");
}

.qwojw7b6x {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14 7.5l2.5.5m-8.25 8.75c.75 0 1.25-1.25 2-1.25s1 .9 1.75.9s1.25-1.15 2-1.15h.5l1.25 1");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

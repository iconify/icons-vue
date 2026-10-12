<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="mf1-_ibir"/><path class="x4wge66qw"/><path class="z4jihqbow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:taxi-sharp" /></template>
<style>
.mf1-_ibir {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.75 13.75l1.85-5.4l.466-1.356L7.5 7h9l1.434-.006l.466 1.356l1.85 5.4v5.75H3.75v-1ZM6.5 19.5v1.75m11-1.75v1.75M4.25 12.5h15.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.x4wge66qw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 16h.01m8.99 0h.01");
}

.z4jihqbow {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 2.75h4.5l.23.97l.54 2.31l.23.97h-7.5l.23-.97l.54-2.31l.23-.97z");
}

</style>

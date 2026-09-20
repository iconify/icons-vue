<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k70w93buq"/><path class="f4yp5uw0u"/><path class="ns_05qbai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:page-resolve-outline-thin" /></template>
<style>
.f4yp5uw0u {
  d: path("M14 18.5a2 2 0 0 1 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k70w93buq {
  d: path("M6 15v-5a6 6 0 0 1 12 0v5l2.5 2.5h-17z");
}

.ns_05qbai {
  d: path("m9 11 2 2 4 -4");
}

</style>

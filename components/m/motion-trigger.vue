<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxhr0dbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:motion-trigger" /></template>
<style>
.xxhr0dbuy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.89 5.908l-3.206 5.179A1.253 1.253 0 0 0 11.75 13h.356a1.5 1.5 0 0 1 1.46 1.844L13 17.25a.946.946 0 0 0 1.67.795l4.301-5.567A1.228 1.228 0 0 0 18 10.5h-.903A1.5 1.5 0 0 1 15.6 8.906l.15-2.406a1.006 1.006 0 0 0-1.86-.592M4 7h5m-6.5 5h4M4 17h5");
}

</style>

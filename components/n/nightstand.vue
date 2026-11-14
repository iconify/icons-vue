<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfx3ddbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nightstand" /></template>
<style>
.jfx3ddbbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.125 4.5h11.75A2.625 2.625 0 0 1 20.5 7.125v6.75a2.625 2.625 0 0 1-2.625 2.625H6.125A2.625 2.625 0 0 1 3.5 13.875v-6.75A2.625 2.625 0 0 1 6.125 4.5m-.625 12v3m13-3v3M3.5 10h17m-10-2.75h3");
}

</style>

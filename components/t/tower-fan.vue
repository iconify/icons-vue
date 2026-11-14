<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vq21b4r8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tower-fan" /></template>
<style>
.vq21b4r8f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 18.5v-14a2 2 0 0 1 2-2h5.5a2 2 0 0 1 2 2v14Zm0 0l-1.75 3h13l-1.75-3M10.25 6v9m3.5-9v9");
}

</style>

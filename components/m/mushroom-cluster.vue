<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs38u89rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mushroom-cluster" /></template>
<style>
.zs38u89rh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 9a4.5 4.5 0 0 1 9 0ZM12 9v12m-9.5-6a3 3 0 0 1 6 0Zm3 0v6m10-8a3 3 0 0 1 6 0Zm3 0v8m-16 0h19");
}

</style>

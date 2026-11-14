<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8d89-b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:play" /></template>
<style>
.u8d89-b9v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.04 6.586l5.005 3.203a2.625 2.625 0 0 1 0 4.422l-5.005 3.203A2.625 2.625 0 0 1 7 15.203V8.797a2.625 2.625 0 0 1 4.04-2.211");
}

</style>

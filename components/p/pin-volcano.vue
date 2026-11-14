<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="an11r1mmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-volcano" /></template>
<style>
.an11r1mmr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.996 17.882l4-7A1.75 1.75 0 0 1 9.516 10h4.968a1.75 1.75 0 0 1 1.52.882l4 7a1.75 1.75 0 0 1-1.52 2.618H5.516a1.75 1.75 0 0 1-1.52-2.618M12 3v4.25m-3.25 0L6.75 4m8.5 3.25l2-3.25");
}

</style>

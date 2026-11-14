<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwsusny-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:triangle-down" /></template>
<style>
.mwsusny-l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.56 4.5h8.88a2.625 2.625 0 0 1 2.27 3.943l-4.44 7.647a2.625 2.625 0 0 1-4.54 0L5.29 8.443A2.625 2.625 0 0 1 7.56 4.5");
}

</style>

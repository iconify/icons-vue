<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdgqmabiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:octagon-cage" /></template>
<style>
.sdgqmabiu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 21.5H8.25L2.5 15.75v-7.5L8.25 2.5h7.5l5.75 5.75v7.5l-5.75 5.75H14m-4 0v-2.75m4 2.75v-2.75");
}

</style>

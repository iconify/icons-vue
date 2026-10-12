<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcjj3vbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:umbrella-stand" /></template>
<style>
.kcjj3vbhl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 10.25v-5a2 2 0 0 0-4 0v.5m9 4.5v-5.5a2 2 0 0 1 4 0v.5m-12.25 5h11.5l-1 10a1 1 0 0 1-1 1h-7.5a1 1 0 0 1-1-1Zm.35 3.5h10.8");
}

</style>

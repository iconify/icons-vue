<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dl02g5b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:plow-blade" /></template>
<style>
.dl02g5b-k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.5H14.5l4.5-5h2.25m-10.75 5v4.75m-7.75 7.5h11.5a3 3 0 0 0 2.9-2.2l1.35-5.3h-9a6 6 0 0 0-5.2 3Z");
}

</style>

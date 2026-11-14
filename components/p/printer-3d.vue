<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fckr85_4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:printer-3d" /></template>
<style>
.fckr85_4v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4h18M10 4h4a1 1 0 0 1 1 1v.379a1.5 1.5 0 0 1-.439 1.06l-1.5 1.5a1.5 1.5 0 0 1-2.122 0l-1.5-1.5A1.5 1.5 0 0 1 9 5.379V5a1 1 0 0 1 1-1m-.25 7.75h4.5A1.75 1.75 0 0 1 16 13.5v5.25a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 8 18.75V13.5a1.75 1.75 0 0 1 1.75-1.75M3 20.5h18");
}

</style>

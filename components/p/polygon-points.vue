<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsu73d-da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:polygon-points" /></template>
<style>
.xsu73d-da {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.218 5.166l.988.156M10.07 17.638l-1.717-.813m-2.492-5.909l.791-2.372M6.5 4.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M16 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m2.25 7.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-5.75 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M3 15a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>

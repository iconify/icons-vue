<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0qcuk6jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shuttlecock" /></template>
<style>
.h0qcuk6jy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 17h6v1a3 3 0 0 1-6 0Zm-.342-1.026l-3.5-10.5A1.5 1.5 0 0 1 6.581 3.5h10.838a1.5 1.5 0 0 1 1.423 1.974l-3.5 10.5A1.5 1.5 0 0 1 13.919 17h-3.838a1.5 1.5 0 0 1-1.423-1.026M12 17V3.5m-5.5 6h11");
}

</style>

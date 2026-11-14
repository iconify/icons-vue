<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr11u5p0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pallet-exchange" /></template>
<style>
.tr11u5p0y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h9m-9 4.5h9M3 4v4.5M7 4v4.5M11 4v4.5m1.5 8h9m-9 4.5h9M13 16.5V21m4-4.5V21m4-4.5V21M14.5 5.25c3 0 5 2.25 5 5.75m-2-1.5l2 2l2-2m-12 9.25c-3 0-5-2.25-5-5.75m-2 1.5l2-2l2 2");
}

</style>

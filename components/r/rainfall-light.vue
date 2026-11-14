<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8w-kpgkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rainfall-light" /></template>
<style>
.m8w-kpgkf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3S6.5 9.5 6.5 13a5.5 5.5 0 0 0 11 0C17.5 9.5 12 3 12 3M7 21.5h10");
}

</style>

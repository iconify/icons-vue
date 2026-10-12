<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfjjg3bvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paperclip-plus" /></template>
<style>
.mfjjg3bvj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m19.5 11.25l-7.4 7.4a4.5 4.5 0 0 1-6.35-6.35l7.95-7.95a3 3 0 0 1 4.25 4.25L10 16.55a1.5 1.5 0 0 1-2.1-2.1l7.1-7.1");
}

</style>

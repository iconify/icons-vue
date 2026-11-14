<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg7ckixpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:speed-bag" /></template>
<style>
.eg7ckixpf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3.5h16m-8 0V7m-1.5 0h3c3 2.5 4.5 5 4.5 8a6 6 0 0 1-12 0c0-3 1.5-5.5 4.5-8Z");
}

</style>

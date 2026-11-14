<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtks48bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:video-support" /></template>
<style>
.vtks48bap {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5H15v10H2.5ZM15 7l5-2.5v8L15 10Zm2 10.25a2 2 0 0 1 4 0c0 1.35-2 1.65-2 2M19 22h.01");
}

</style>

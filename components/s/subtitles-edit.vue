<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hk393lfwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:subtitles-edit" /></template>
<style>
.hk393lfwh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 19h-10V5h19v8.1M6 12h3.5m3 0H18M6 15.5h9m0 5.75l.25-2L19.5 15l1.75 1.75L17 21Z");
}

</style>

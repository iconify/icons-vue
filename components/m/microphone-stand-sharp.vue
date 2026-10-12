<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrlvrvbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:microphone-stand-sharp" /></template>
<style>
.rrlvrvbfw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.75h5v7.5h-5zm2.5 7.5v8.5m0 0l-5 2.5m5-2.5l5 2.5m-5-2.5v2.5M9.75 13h4.5");
}

</style>

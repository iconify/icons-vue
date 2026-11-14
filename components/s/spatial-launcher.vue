<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlp69zb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spatial-launcher" /></template>
<style>
.tlp69zb8j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 6.5h4l-.75 4h-4Zm6.75 0h4l-.75 4h-4Zm6.75 0h4l-.75 4h-4ZM3 13.5h4l-.75 4h-4Zm6.75 0h4l-.75 4H9Zm6.75 0h4l-.75 4h-4Z");
}

</style>

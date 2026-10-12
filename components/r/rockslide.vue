<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anh1dmbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rockslide" /></template>
<style>
.anh1dmbnn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.01 20.55l5.48-15.1q.26-.7.63-.05l1.26 2.2q.37.65.07 1.34l-.4.87q-.3.69-.05 1.4l3.25 9.33q.25.71-.5.71H3.5q-.75 0-.49-.7M15.09 5.22l.38-.09q.69-.15 1.2.32l.29.27q.51.48.17 1.08l-.18.31q-.35.61-1.05.59l-.63-.01q-.7-.01-.75-.71l-.06-.91q-.05-.69.63-.85m2.68 6.08l.3.15q.54.28.61.87l.04.33q.08.6-.48.81l-.29.1q-.56.21-1.01-.19l-.41-.35q-.45-.4-.1-.88l.46-.63q.35-.49.88-.21m-1.85 9.38l.41-1.36q.17-.57.67-.9l.5-.34q.5-.33 1.01-.02l.23.13q.51.31 1.02 0l.23-.13q.51-.31.82.2l.13.23q.31.51.31 1.11v1.05q0 .6-.6.6h-4.3q-.6 0-.43-.57");
}

</style>

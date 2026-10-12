<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rx33sxbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rockslide-sharp" /></template>
<style>
.rx33sxbol {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.01 20.55l5.48-15.1l.26-.7l.37.65l1.26 2.2l.37.65l-.3.69l-.4.87l-.3.69l.25.71l3.25 9.33l.25.71H2.75zM15.09 5.22l.38-.09l.69-.15l.51.47l.29.27l.51.48l-.34.6l-.18.31l-.35.61l-.7-.02l-.63-.01l-.7-.01l-.05-.7l-.06-.91l-.05-.69zm2.68 6.08l.3.15l.54.28l.07.59l.04.33l.08.6l-.56.21l-.29.1l-.56.21l-.45-.4l-.41-.35l-.45-.4l.35-.48l.46-.63l.35-.49zm-1.85 9.38l.41-1.36l.17-.57l.5-.33l.5-.34l.5-.33l.51.31l.23.13l.51.31l.51-.31l.23-.13l.51-.31l.31.51l.13.23l.31.51v2.25h-5.5z");
}

</style>

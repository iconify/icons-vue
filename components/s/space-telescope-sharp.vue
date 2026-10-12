<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w06hrdbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:space-telescope-sharp" /></template>
<style>
.w06hrdbaf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9.5h14v5h-14zm15.06-.14l1.38-1.72l.31-.39l.4.3l.2.15l.4.3l-.31.39l-1.38 1.72l-.31.39l-.4-.3l-.2-.15l-.4-.3zM11 7v2.5m0 5V17M8.5 2.75h5V7h-5zM8.5 17h5v4.25h-5z");
}

</style>

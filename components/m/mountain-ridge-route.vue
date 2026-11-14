<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdx45swpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mountain-ridge-route" /></template>
<style>
.xdx45swpc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 20l5-12l4.5 6l4.5-6.5l5 12.5M7.5 4.75h.01m2.24 2h.01M12 9h.01m2.24-2.5h.01m2.24-2.25h.01");
}

</style>

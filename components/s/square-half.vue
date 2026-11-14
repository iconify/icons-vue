<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utfdj7bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:square-half" /></template>
<style>
.utfdj7bsp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5H5.5a2 2 0 0 0-2 2v13a2 2 0 0 0 2 2H12Zm0 0h6.5a2 2 0 0 1 2 2v13a2 2 0 0 1-2 2H12");
}

</style>

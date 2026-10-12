<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_shwobhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:witch-hat-sharp" /></template>
<style>
.l_shwobhx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.55 17.25h9.7l-.27-.75l-2.46-7l-.27-.75l.55-.58l3.15-3.34l.55-.58l-.77.2l-5.21 1.35l-.77.2l-.32.73l-4.36 9.79l-.32.73zm.53-3h8.11m-13.44 3h18.5");
}

</style>

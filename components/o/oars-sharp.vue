<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfb-fbm8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oars-sharp" /></template>
<style>
.wfb-fbm8u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 3.25L5.5 5.5m1 1l6.75 6.75m1.55.15l4.1 2.25l1.1.6l.21 1.23l.33 2.04l.21 1.23l-1.23-.21l-2.04-.33l-1.23-.21l-.6-1.1l-2.25-4.1l-.6-1.1l.45-.45l.45-.45z");
}

</style>

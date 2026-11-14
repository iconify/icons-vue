<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ws198bctf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sun-dim" /></template>
<style>
.ws198bctf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0Zm5-8.75h.01M12 20.75h.01M3.25 12h.01m17.49 0h.01M5.75 5.75h.01m12.49 0h.01M5.75 18.25h.01m12.49 0h.01");
}

</style>

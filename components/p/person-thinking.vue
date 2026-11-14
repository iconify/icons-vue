<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe9d5vbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:person-thinking" /></template>
<style>
.xe9d5vbdp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 21.5v-3c-2-1.25-2.75-3.25-2.75-5.25C2.5 10 5 7.5 8 7.5s5.5 2.25 5.5 5.25l1 2.5c.25.5 0 .75-.5.75h-.5v1.75c0 .75-.75 1.5-1.75 1.5H10.5v2.25M15.25 5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm0 5.5h.01");
}

</style>

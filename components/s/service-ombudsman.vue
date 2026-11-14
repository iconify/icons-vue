<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi35eez2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:service-ombudsman" /></template>
<style>
.fi35eez2z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.964 9.854l3.89-3.89a1.75 1.75 0 0 1 2.474 0l.708.708a1.75 1.75 0 0 1 0 2.474l-3.89 3.89a1.75 1.75 0 0 1-2.474 0l-.708-.708a1.75 1.75 0 0 1 0-2.474m5.286 1.396l8.25 8.25M4.25 18h5.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75h-5.5a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 4.25 18");
}

</style>

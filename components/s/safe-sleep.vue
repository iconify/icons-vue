<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alzlfxbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:safe-sleep" /></template>
<style>
.alzlfxbbd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8v12.5M21 8v12.5M3 11h18M3 17h18M7.5 11v6m4.5-6v6m4.5-6v6m-4-14.5A3 3 0 1 0 15 7a2.25 2.25 0 0 1-2.5-4.5");
}

</style>

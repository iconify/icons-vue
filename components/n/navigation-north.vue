<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bltzq3bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:navigation-north" /></template>
<style>
.bltzq3bps {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.286 4.644l3.042 5.069A1.069 1.069 0 0 1 15 11.25l-2.423-1.01a1.5 1.5 0 0 0-1.154 0L9 11.25a1.069 1.069 0 0 1-1.328-1.537l3.042-5.069a1.5 1.5 0 0 1 2.572 0M8.5 21.5v-6l7 6v-6");
}

</style>

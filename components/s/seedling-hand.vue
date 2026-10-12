<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eu2jnpb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seedling-hand" /></template>
<style>
.eu2jnpb_q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.25v7.5m3-6.5h2.5l2.1-1.1a2 2 0 0 1 .95-.25h2.45a1.5 1.5 0 0 1 0 3H11.5m-5.75 4.35h6.6a3 3 0 0 0 1.85-.65l5.6-4.4a1.5 1.5 0 0 0-1.85-2.35l-3.2 2.5m-1.5-4.6V7m0 0C13 4.5 11.5 3.25 9 3.25C9.25 5.75 10.75 7 13.25 7m0 0C13.5 4.5 15 3.25 17.5 3.25C17.25 5.75 15.75 7 13.25 7");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rztj0fbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:taekwondo-kick" /></template>
<style>
.rztj0fbge {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm3.75 4.75L9.5 14L8 21.5M9.5 14l11-10M8.75 10.5L3.5 13");
}

</style>

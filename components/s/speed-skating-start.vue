<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4uehwpqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:speed-skating-start" /></template>
<style>
.b4uehwpqv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.5 6.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM13 10l-6 1.5l4 3.75L9.5 19M7 11.5L3.5 18m9.5-8l1.5 4.75M20 12.5v8");
}

</style>

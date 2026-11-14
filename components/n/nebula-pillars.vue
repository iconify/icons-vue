<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6du8p8qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nebula-pillars" /></template>
<style>
.n6du8p8qw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21h19M3 21l1.5-9.5q.5-2 1 0L7 21m2.75 0L11.5 7.5q.5-2 1 0L14.25 21M17 21l1.5-6.5q.5-2 1 0L21 21M18.75 3v5m-2.5-2.5h5");
}

</style>

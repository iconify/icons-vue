<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnm90acbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shutters-interior" /></template>
<style>
.jnm90acbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 3L3 5v14l4.5 2Zm9 0L21 5v14l-4.5 2ZM3 10h4.5M3 14h4.5m9-4H21m-4.5 4H21");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhh7e5g-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sandstone" /></template>
<style>
.rhh7e5g-k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.642 17.87l.794-9.132a1.5 1.5 0 0 1 .689-1.136l4.416-2.81a1.5 1.5 0 0 1 .999-.222l9.748 1.272a1.5 1.5 0 0 1 1.302 1.377l.791 10.67a1.5 1.5 0 0 1-1.496 1.611H4.136a1.5 1.5 0 0 1-1.494-1.63M3 11.5l18-1.75m-18.25 6l18.5-1.5");
}

</style>

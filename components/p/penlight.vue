<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="woj0a1bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:penlight" /></template>
<style>
.woj0a1bbc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.236 16.963l7.278-6.107a1.75 1.75 0 0 1 2.465.216a1.75 1.75 0 0 1-.215 2.465l-7.278 6.107a1.75 1.75 0 0 1-2.465-.216a1.75 1.75 0 0 1 .215-2.465M4.23 15.01l3.447-2.892M15.75 9.75l4.75-5.5m-3.25 7.25l4.25-2.25m-7-.75l.75-5");
}

</style>

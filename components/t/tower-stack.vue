<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2v3r7b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tower-stack" /></template>
<style>
.b2v3r7b4s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 15.5h12.5A1.75 1.75 0 0 1 20 17.25v2.5a1.75 1.75 0 0 1-1.75 1.75H5.75A1.75 1.75 0 0 1 4 19.75v-2.5a1.75 1.75 0 0 1 1.75-1.75m2-6h8.5A1.75 1.75 0 0 1 18 11.25v2.5a1.75 1.75 0 0 1-1.75 1.75h-8.5A1.75 1.75 0 0 1 6 13.75v-2.5A1.75 1.75 0 0 1 7.75 9.5m4.237-.319l4.066-.871a1.5 1.5 0 0 0 1.157-1.761l-.412-2.058a1.5 1.5 0 0 0-1.785-1.172l-4.066.871A1.5 1.5 0 0 0 9.79 5.951l.412 2.058a1.5 1.5 0 0 0 1.785 1.172");
}

</style>

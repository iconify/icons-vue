<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sinbrccnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mesh-wifi" /></template>
<style>
.sinbrccnt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 4.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-7.25 14a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm14.5 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-6-11.75L6 16.25m7.25-9.5l4.75 9.5M7.25 18.5h9.5");
}

</style>

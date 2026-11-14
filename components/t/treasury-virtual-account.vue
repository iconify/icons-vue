<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhf7v-bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:treasury-virtual-account" /></template>
<style>
.mhf7v-bks {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8V5A2.5 2.5 0 0 1 7 2.5h1m8 0h1A2.5 2.5 0 0 1 19.5 5v3m-15 8v3A2.5 2.5 0 0 0 7 21.5h1m8 0h1a2.5 2.5 0 0 0 2.5-2.5v-3M10.75 2.5h2.5m-2.5 19h2.5M4.5 10.75v2.5m15-2.5v2.5m-11-8v13.5m3-11.25h4");
}

</style>

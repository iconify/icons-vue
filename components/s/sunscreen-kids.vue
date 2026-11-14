<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmm1qrppy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sunscreen-kids" /></template>
<style>
.gmm1qrppy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 2.5h9v2.75h-9Zm.75 2.75L5.75 15.5h5L12 5.25M7.625 15.5h1.25a2.625 2.625 0 0 1 2.625 2.625v.75A2.625 2.625 0 0 1 8.875 21.5h-1.25A2.625 2.625 0 0 1 5 18.875v-.75A2.625 2.625 0 0 1 7.625 15.5m5.14-10.946a5.5 5.5 0 0 1 1.985 10.209M17.75 4L19 2.75M20.25 10h1.5m-4 6L19 17.25");
}

</style>

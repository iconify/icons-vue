<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5e8qrb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paragraph" /></template>
<style>
.x5e8qrb0u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 3.75h-2.25a4.5 4.5 0 0 0 0 9H13Zm0 0v16.5m0-16.5h4.75m0 0v16.5");
}

</style>

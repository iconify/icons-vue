<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc4vtebuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:popsicle" /></template>
<style>
.rc4vtebuf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 8.25a5.5 5.5 0 0 1 11 0v7.5A1.25 1.25 0 0 1 16.25 17h-8.5a1.25 1.25 0 0 1-1.25-1.25Zm3.25-.75v6m4.5-6v6M12 17v4.25");
}

</style>

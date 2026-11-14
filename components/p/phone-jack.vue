<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8ee7eo9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:phone-jack" /></template>
<style>
.f8ee7eo9z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 4.5h11a2 2 0 0 1 2 2v10h-4v3h-7v-3h-4v-10a2 2 0 0 1 2-2M9 8v3.5M12 8v3.5M15 8v3.5");
}

</style>

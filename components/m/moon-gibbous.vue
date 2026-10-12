<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0cwj2-md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:moon-gibbous" /></template>
<style>
.o0cwj2-md {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75a9.25 9.25 0 0 1 0 18.5a4.75 9.25 0 0 1 0-18.5M6.05 4.91a9.25 9.25 0 0 0 0 14.18");
}

</style>

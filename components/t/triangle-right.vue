<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7p0yj1eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:triangle-right" /></template>
<style>
.o7p0yj1eb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.443 5.29l7.647 4.44a2.625 2.625 0 0 1 0 4.54l-7.647 4.44A2.625 2.625 0 0 1 4.5 16.44V7.56a2.625 2.625 0 0 1 3.943-2.27");
}

</style>

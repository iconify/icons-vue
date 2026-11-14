<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8d28ymxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:school-band" /></template>
<style>
.f8d28ymxm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10h12v3h-12Zm12 0L21 6.5v10L14.5 13ZM6 10V6.5M9 10V6.5m3 3.5V6.5M6 13v4h6v-4");
}

</style>

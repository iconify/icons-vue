<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owcd9jb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pregnancy-week" /></template>
<style>
.owcd9jb7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.717 17.992A4.4 4.4 0 0 1 10.5 18l-.25 3.5H5V17c-.75-1.5-1.25-4-1-6c.25-1.5.75-2.5 1.5-2.5h3c1 0 1.5.5 1.75 1.5l.25 1c1.45.435 2.564 1.206 3.195 2.168M5.25 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m11 10.5h3.5A1.75 1.75 0 0 1 21.5 17v3a1.75 1.75 0 0 1-1.75 1.75h-3.5A1.75 1.75 0 0 1 14.5 20v-3a1.75 1.75 0 0 1 1.75-1.75m-1.75 2.5h7m-5-3.75v1.5m3-1.5v1.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9f-bf4yj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pilgrim-staff" /></template>
<style>
.x9f-bf4yj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.25V6a2.5 2.5 0 0 1 5 0m-5 1.5l-5.5 2m0 0a1.25 1.25 0 0 1 .9 2.15c1.3.45 2.1 1.4 2.1 2.85a3 3 0 0 1-6 0c0-1.45.8-2.4 2.1-2.85a1.25 1.25 0 0 1 .9-2.15");
}

</style>

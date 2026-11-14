<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8wa-8bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:measurement" /></template>
<style>
.u8wa-8bey {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.161 15.889L15.889 3.161l4.95 4.95L8.111 20.839Zm3.182-3.182l2.475 2.475m-.354-4.596L9.879 12m.707-3.536l2.475 2.475m-.354-4.596l1.414 1.414");
}

</style>

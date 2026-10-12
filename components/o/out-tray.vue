<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k16svj28z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:out-tray" /></template>
<style>
.k16svj28z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 13.25h15.5q1.5 0 1.22 1.47l-.94 5.06q-.28 1.47-1.78 1.47H5.75q-1.5 0-1.78-1.47l-.94-5.06q-.28-1.47 1.22-1.47m3.75 4h8M12 11V3M8.75 6.25L12 3l3.25 3.25");
}

</style>

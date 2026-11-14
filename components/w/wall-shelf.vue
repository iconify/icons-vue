<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qncwfibaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wall-shelf" /></template>
<style>
.qncwfibaj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14h19M4 14v4m16-4v4M9.25 5h5.5a1.75 1.75 0 0 1 1.75 1.75v5.5A1.75 1.75 0 0 1 14.75 14h-5.5a1.75 1.75 0 0 1-1.75-1.75v-5.5A1.75 1.75 0 0 1 9.25 5M12 5v3.5");
}

</style>

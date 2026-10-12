<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="loln9bcia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ship-flag" /></template>
<style>
.loln9bcia {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.72 3.72l14.31 4.31q.72.22 0 .44L5.72 12.78Q5 13 5 12.25v-8q0-.75.72-.53M5 8.25h7m-7 13V2.75m-2.25 18.5h4.5");
}

</style>

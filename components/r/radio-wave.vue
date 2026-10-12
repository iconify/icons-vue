<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mof8chbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:radio-wave" /></template>
<style>
.mof8chbiz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12q2.31-7.995 4.62 0c2.31 7.995 3.08 5.33 4.63 0s3.08-5.33 4.62 0s3.08 5.33 4.63 0");
}

</style>

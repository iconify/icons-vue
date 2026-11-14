<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d18xyjbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:phishing-qr" /></template>
<style>
.d18xyjbet {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5H10V10H3.5Zm10.5 0h6.5V10H14ZM3.5 14H10v6.5H3.5Zm3.25-7.25h.01m10.49 0h.01M6.75 17.25h.01M19.5 14.5V19a2.25 2.25 0 0 1-4.5 0v-1.25");
}

</style>

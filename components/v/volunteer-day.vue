<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mim_0imxh"/><path class="w0zq_0brj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:volunteer-day" /></template>
<style>
.mim_0imxh {
  d: path("M12 11.5S7.5 9 7.5 5.75C7.5 4.25 8.6 3 10 3c.9 0 1.6.5 2 1.25C12.4 3.5 13.1 3 14 3c1.4 0 2.5 1.25 2.5 2.75C16.5 9 12 11.5 12 11.5ZM2.5 15h3L9 17h4.25a1.25 1.25 0 0 1 0 2.5H9.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w0zq_0brj {
  d: path("M5.5 21H13l7-4.5c.75-.5.5-1.75-.5-1.75c-.5 0-1.25.5-3.5 1.75");
}

</style>

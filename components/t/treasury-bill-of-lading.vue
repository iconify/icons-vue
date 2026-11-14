<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y__aag1qj"/><path class="pecaz-bmy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:treasury-bill-of-lading" /></template>
<style>
.pecaz-bmy {
  d: path("M18.25 2v2.25h2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y__aag1qj {
  d: path("M21.5 11.8V21h-19V8h9.2M6 11v7m3.5-7v7m6.5-6.2V21m-2.75-8.5v4m5.5-4v4M14.5 2h3.75l2.25 2.25V9h-6Z");
}

</style>

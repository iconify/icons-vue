<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o0g7m7bdp"/><path class="w21dwcc-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:treasury-iso20022" /></template>
<style>
.o0g7m7bdp {
  d: path("M4.5 2.5h15v19h-15Zm3.5 4h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w21dwcc-k {
  d: path("m10 11l-2.25 2.75L10 16.5m4-5.5l2.25 2.75L14 16.5m-1.25-6l-1.5 6.5");
}

</style>

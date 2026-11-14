<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h8y1jkbzs"/><path class="d___vbc1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mass-vs-weight" /></template>
<style>
.d___vbc1j {
  d: path("M4 9.5h4l1.5 10h-7ZM16.25 5v14.5m-3 0h6M12.5 7H20m-7.5 0v3.5m-1.5 0a1.5 1.5 0 0 0 3 0ZM20 7v3.5m-1.5 0a1.5 1.5 0 0 0 3 0Z");
}

.h8y1jkbzs {
  d: path("M3.5 7a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

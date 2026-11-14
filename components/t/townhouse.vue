<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ooeq3nbuk"/><path class="dki9w5bhg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:townhouse" /></template>
<style>
.dki9w5bhg {
  d: path("M4.75 21.5v-4h2v4m4.25 0v-4h2v4m4.25 0v-4h2v4M5.75 13h.01M12 11.5h.01m6.24 2.5h.01");
}

.ooeq3nbuk {
  d: path("M2.5 21.5v-12l3.25-3L9 9.5v-2L12 4l3 3.5v3l3.25-3l3.25 3v11ZM9 9.5v12m6-11v11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

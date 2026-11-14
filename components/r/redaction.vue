<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o0g7m7bdp"/><path class="ud7o7dbuz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:redaction" /></template>
<style>
.o0g7m7bdp {
  d: path("M4.5 2.5h15v19h-15Zm3.5 4h8");
}

.ud7o7dbuz {
  fill: currentColor;
  d: path("M8 9.75h8v2.5H8ZM8 15h5v2.5H8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

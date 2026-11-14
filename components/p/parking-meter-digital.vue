<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ew2_6kbzi"/><path class="qsthmvb8g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:parking-meter-digital" /></template>
<style>
.ew2_6kbzi {
  d: path("M6.5 2.5h11v11h-11Zm5.5 11v8m-3.5 0h7");
}

.qsthmvb8g {
  d: path("M9 5.5h6V9H9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

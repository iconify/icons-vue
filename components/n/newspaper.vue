<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yg5c6ykby"/><path class="eyrp32b-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:newspaper" /></template>
<style>
.eyrp32b-w {
  d: path("M6.5 7.5h7v4h-7Zm0 7h7m-7 2.5H11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yg5c6ykby {
  d: path("M17 20H5.5A2.5 2.5 0 0 1 3 17.5v-12A1.5 1.5 0 0 1 4.5 4h11A1.5 1.5 0 0 1 17 5.5V18a2 2 0 0 0 4 0V9h-4Z");
}

</style>

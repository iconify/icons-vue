<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h8-_f4cyr"/><path class="j7ta_mt_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ram-stick" /></template>
<style>
.h8-_f4cyr {
  d: path("M2.5 5.5h19v9h-19Z");
}

.j7ta_mt_r {
  d: path("M5.5 8.25H10v3.5H5.5Zm8.5 0h4.5v3.5H14ZM5.5 14.5V18m3-3.5V18m3-3.5V18m4-3.5V18m3-3.5V18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zf83j-83u"/><path class="qumzlubap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:marshal-post" /></template>
<style>
.qumzlubap {
  d: path("M7 20.5V16h3.5v4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zf83j-83u {
  d: path("m3.5 11l5.25-5L14 11v9.5H3.5Zm14 9.5v-17m0 0h4l-1.25 2.25L21.5 8h-4");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yqc_33hqc"/><path class="mggja2bnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:safe-deposit-rent" /></template>
<style>
.mggja2bnq {
  d: path("M4.75 5h6v4.5h-6Zm8.5 0h6v4.5h-6Zm-8.5 9h6v4.5h-6ZM6.5 7.25H9m6 0h2.5m-11 9H9m5.5-1.75h4l3.25 3.25l-4 4l-3.25-3.25Zm2.25 2.25h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yqc_33hqc {
  d: path("M13.6 21.5H2.5v-19h19v11.1");
}

</style>

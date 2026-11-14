<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mie9b5bhx"/><path class="sg_8t8v0c"/><path class="xuv-p6wvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:marketing-automation" /></template>
<style>
.mie9b5bhx {
  d: path("M4.206 7.5a9 9 0 1 1 0 9");
}

.sg_8t8v0c {
  d: path("m4.5 3.5l3 .75L6.75 7M7 8.5h10v7H7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xuv-p6wvo {
  d: path("M7.25 9.25L12 12.5l4.75-3.25");
}

</style>

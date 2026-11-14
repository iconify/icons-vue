<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vi6v2b-ho"/><path class="btm028itd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:retail-unit" /></template>
<style>
.btm028itd {
  d: path("M8.5 13h7v7.5h-7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vi6v2b-ho {
  d: path("m3 9l1.5-5h15L21 9Zm1.5 2v9.5h15V11");
}

</style>

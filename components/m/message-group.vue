<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pvqaf_bvd"/><path class="f87p7rcdn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:message-group" /></template>
<style>
.f87p7rcdn {
  d: path("M8 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1.5 6.75c0-1.5 1.5-2.25 3.5-2.25s3.5.75 3.5 2.25M14 7.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm1.5 4.25c1.75 0 2.5 1 2.5 2.25");
}

.pvqaf_bvd {
  d: path("M2.5 5.5A2.5 2.5 0 0 1 5 3h14a2.5 2.5 0 0 1 2.5 2.5V15a2.5 2.5 0 0 1-2.5 2.5h-8L6.5 21v-3.5H5A2.5 2.5 0 0 1 2.5 15Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

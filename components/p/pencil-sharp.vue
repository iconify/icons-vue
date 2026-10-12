<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zx4_nwq8q"/><path class="qjy-hbb8v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pencil-sharp" /></template>
<style>
.qjy-hbb8v {
  d: path("m18.71 7.76l-2.47-2.47l-.71-.71l-.71.71l-7.41 7.41l-.71.71l-.35.94l-1.6 4.31l-.35.94l.94-.35l4.31-1.6l.94-.35l.71-.71l7.41-7.41l.71-.71zm-8.12 9.54L6.7 13.41");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zx4_nwq8q {
  d: path("m20.48 5.99l-2.47-2.47l-.71-.71l-.71.71l-.35.35l-.71.71l.71.71l2.47 2.47l.71.71l.71-.71l.35-.35l.71-.71z");
}

</style>

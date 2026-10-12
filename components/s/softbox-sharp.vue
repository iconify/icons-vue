<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="cyc7r13hj"/><path class="tt5mxob4e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:softbox-sharp" /></template>
<style>
.cyc7r13hj {
  d: path("M3.25 2.75h17.5v12.5H3.25z");
}

.tt5mxob4e {
  d: path("M6.75 5.75h10.5v6.5H6.75zM4.6 3.6l2.15 2.15M19.4 3.6l-2.15 2.15M4.6 14.4l2.15-2.15M19.4 14.4l-2.15-2.15m-5.25 3v6m-3.75 0l3.75-3l3.75 3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

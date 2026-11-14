<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eoz3zibrm"/><path class="ca0vv5bxe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:medical-bill" /></template>
<style>
.ca0vv5bxe {
  d: path("M14 7c-.5-.75-1.25-1-2-1c-1.25 0-2 .75-2 1.75c0 2.25 4 1.5 4 4c0 1-.75 1.75-2 1.75c-1 0-1.75-.5-2-1.25m2-7.75V15m-4 3h8");
}

.eoz3zibrm {
  d: path("M4.5 2.5h15v19h-15Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

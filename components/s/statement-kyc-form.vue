<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eoz3zibrm"/><path class="wslum4b8e"/><path class="cn0m-bbkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:statement-kyc-form" /></template>
<style>
.cn0m-bbkl {
  d: path("M9.25 7.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0ZM8.75 12c.25-1.25 3.25-1.25 3.5 0M7.5 15h9m-9 3.25H13");
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

.wslum4b8e {
  d: path("M7.5 5.5h6V12h-6Z");
}

</style>

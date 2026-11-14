<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eoz3zibrm"/><path class="hfbu4myfe"/><path class="rlvf0f4si"/><path class="mufoqob7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:patient-check-in" /></template>
<style>
.eoz3zibrm {
  d: path("M4.5 2.5h15v19h-15Z");
}

.hfbu4myfe {
  d: path("M7 5h10v8H7Z");
}

.mufoqob7b {
  fill: currentColor;
  d: path("M8.5 16.25h7v1.5h-7Z");
}

.rlvf0f4si {
  d: path("m9.5 9l1.75 1.75L14.5 7.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

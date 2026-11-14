<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eoz3zibrm"/><path class="ccq_7bbpd"/><path class="ofw-vbs-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pedestrian-signal-walk" /></template>
<style>
.ccq_7bbpd {
  d: path("M11.5 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm1 3L11 13.25l2.25 2.25V19M11 13.25l-1.25 3l-1.5 2.25");
}

.eoz3zibrm {
  d: path("M4.5 2.5h15v19h-15Z");
}

.ofw-vbs-c {
  d: path("m8.75 11l3-2l3 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

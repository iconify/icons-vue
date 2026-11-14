<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fa12jhytk"/><path class="a-lfijbyz"/><path class="knt1fachy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:presenter-timer" /></template>
<style>
.a-lfijbyz {
  d: path("m6 9.25l3-2.5l2.5 1.5l4-3M14.25 18a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Z");
}

.fa12jhytk {
  d: path("M15.4 12H2.5V2.5h17v9.1M9 12l-4 9.5m8-9.5l.504 1.198");
}

.knt1fachy {
  d: path("M18 16v2l1.5.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vh2teb39z"/><path class="nz093wc7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:viewing-feedback" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nz093wc7m {
  d: path("m12.588 6.941l.239.484a1.5 1.5 0 0 0 1.129.82l.534.078a.655.655 0 0 1 .363 1.118l-.386.377a1.5 1.5 0 0 0-.432 1.327l.092.532a.655.655 0 0 1-.951.691l-.478-.251a1.5 1.5 0 0 0-1.396 0l-.478.251a.655.655 0 0 1-.951-.691l.092-.532a1.5 1.5 0 0 0-.432-1.327l-.386-.377a.655.655 0 0 1 .363-1.118l.534-.078a1.5 1.5 0 0 0 1.129-.82l.239-.484a.655.655 0 0 1 1.176 0");
}

.vh2teb39z {
  d: path("M5 2.5h14A2.5 2.5 0 0 1 21.5 5v9.5A2.5 2.5 0 0 1 19 17h-4.5L12 20.5L9.5 17H5a2.5 2.5 0 0 1-2.5-2.5V5A2.5 2.5 0 0 1 5 2.5");
}

</style>

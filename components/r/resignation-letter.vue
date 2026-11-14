<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c735_mbvw"/><path class="rc5m4sbbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:resignation-letter" /></template>
<style>
.c735_mbvw {
  d: path("M11.7 19H2.5V5h19v8.6");
}

.rc5m4sbbr {
  d: path("m2.5 7l9.5 6l9.5-6m-7 10.25h6.75m-2.5-2.5l2.5 2.5l-2.5 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

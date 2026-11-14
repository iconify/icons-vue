<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="drre1c3je"/><path class="sh8arxgwu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nights-stay" /></template>
<style>
.drre1c3je {
  d: path("M13 3a9 9 0 1 0 8 11a7 7 0 0 1-8-11Z");
}

.sh8arxgwu {
  d: path("m17.75 4.75l.735 1.739l1.88.161l-1.426 1.236l.427 1.839l-1.616-.975l-1.616.975l.427-1.839l-1.426-1.236l1.88-.161Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

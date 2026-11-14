<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pwckntp7w"/><path class="bzgygt0_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:police-tourist" /></template>
<style>
.bzgygt0_t {
  d: path("M13.467 13.312L11.5 12l-2.25 1.5L10 11L8 9.25h2.5l1-2.5l1 2.5H15L13 11l.646 2.155M18 21.75c-2-2-3-3.5-3-4.75a3 3 0 0 1 6 0c0 1.25-1 2.75-3 4.75ZM18 17h.01");
}

.pwckntp7w {
  d: path("M13.374 20.543q-.9.525-1.874.957c-4.5-2-8-5.5-8-10.5V5.25l8-2.75l8 2.75V11q0 .208-.008.412");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

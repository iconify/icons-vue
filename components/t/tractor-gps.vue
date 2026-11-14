<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wid13xjkn"/><path class="mv9qv3bnp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tractor-gps" /></template>
<style>
.mv9qv3bnp {
  d: path("M7.75 17.25a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm-5.5 1.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm15.75-9c.05.1-2.95-2.5-3-4.75a3 3 0 0 1 6 0c.05 2.25-2.95 4.85-3 4.75ZM18 5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wid13xjkn {
  d: path("M2.5 13.75h5.25v2.75H2.5Zm5.25 0V10a.75.75 0 0 1 .75-.75h3.75l1 5.25");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="atvtat2wa"/><path class="fl2h-1buh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:trophy-star" /></template>
<style>
.atvtat2wa {
  d: path("M7 3.5h10v6a5 5 0 0 1-10 0Zm0 2H5a2 2 0 0 0 0 4h2m10-4h2a2 2 0 0 1 0 4h-2m-5 5V20m-4 0h8");
}

.fl2h-1buh {
  d: path("m12 5.75l.735 1.739l1.88.161l-1.426 1.236l.427 1.839L12 9.75l-1.616.975l.427-1.839L9.385 7.65l1.88-.161Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d5jo19m1a"/><path class="xddcc2bdh"/><path class="t5mofjtby"/><path class="qupeo_3fy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:refactor" /></template>
<style>
.d5jo19m1a {
  d: path("M8.5 8.5h7v7h-7Z");
}

.qupeo_3fy {
  d: path("m10 2l2 2l-2 2");
}

.t5mofjtby {
  d: path("m14 18l-2 2l2 2m-6-3.072A8 8 0 0 1 12 4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xddcc2bdh {
  d: path("M16 5.072A8 8 0 0 1 12 20");
}

</style>

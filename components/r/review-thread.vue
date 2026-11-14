<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zc_jjc_ve"/><path class="sfcrlxr5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:review-thread" /></template>
<style>
.sfcrlxr5f {
  d: path("M8 6.25V4.5a2 2 0 0 1 2-2h9.5a2 2 0 0 1 2 2V16l-2.75-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zc_jjc_ve {
  d: path("M2.5 11a2 2 0 0 1 2-2H14a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H8.5L5 21.5V19h-.5a2 2 0 0 1-2-2Z");
}

</style>

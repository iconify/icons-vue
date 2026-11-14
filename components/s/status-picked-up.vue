<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rspbnh89v"/><path class="vbq9qpbby"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:status-picked-up" /></template>
<style>
.rspbnh89v {
  d: path("M13.534 20.688L12 21.5L3.5 17V7L12 2.5L20.5 7v5.282");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vbq9qpbby {
  d: path("m3.5 7l8.5 4.5L20.5 7M12 11.5v5.3m0 2.4v2.3M7.75 4.75l8.5 4.5M14.75 18l2 2L21 15.75");
}

</style>
